Data augmentation project
augumentation 만들어보기!

decalcomanie 형태로 만들어보자
cifar-100, cifar-10 은 대부분 데칼코마니 형태를 취해도 sementic이 유지가 되니까 잘 작동하지 않을까..?

# (21-1) 실전기계학습

## Result(cifar-100, resnet34)

|Dataset|DA|Acc|
|------|---|---|
|CIFAR-100|MIXUP|78.640|
|CIFAR-100|MIXUP(alpha=0.4)|79.750|
|CIFAR-100|horizondecalcomanie|76.670|
|CIFAR-100|random decalcomanie|77.070|

## décalcomanie
### horizon은 가로 데칼 ramdom은 가로세로 다 랜덤으로 하는거임 
![decal](./git_img/decal.png)_
