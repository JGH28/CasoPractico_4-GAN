# Code Citations

## License: unknown
https://github.com/GRajaraju/CV/tree/ad928335ef418eae4ae1b5927b45fb8df5bf597b/DCGAN.py

```
):
        super(Discriminator, self).__init__()
        self.main = nn.Sequential(
            nn.Conv2d(3, 64, 4, 2, 1, bias=False),
            nn.LeakyReLU(0.2, inplace=True),
            nn.Conv2d
```


## License: unknown
https://github.com/siddhanthiyer-99/Distributed-Training-of-GANs/tree/8178d8d6412330b85000110f2757aa596ce5470c/dataparallelgan.py

```
nn.Module):
    def __init__(self):
        super(Discriminator, self).__init__()
        self.main = nn.Sequential(
            nn.Conv2d(3, 64, 4, 2, 1, bias=False),
            nn.LeakyReLU(0.2
```


## License: MIT
https://github.com/arioobarzan/Multi-Fed-GAN/tree/c3711dbf6b5098653a5c742f51a106f9b5d71d36/pytorch/DistributedGanPytorch_fixed_crypten.py

```
.__init__()
        self.main = nn.Sequential(
            nn.Conv2d(3, 64, 4, 2, 1, bias=False),
            nn.LeakyReLU(0.2, inplace=True),
            nn.Conv2d(64, 128, 4, 2
```


## License: unknown
https://github.com/jorcus/Computer-Vision-A-Z/tree/c917567795929fb70084e29ddb39bf5bddad600a/Module-3-GANs/dcgan.py

```
nn.LeakyReLU(0.2, inplace=True),
            nn.Conv2d(512, 1, 4, 1, 0, bias=False),
            nn.Sigmoid()
        )

    def forward(self, input):
        output = self.main(input)
        return
```

