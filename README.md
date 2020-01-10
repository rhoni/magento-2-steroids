# magento-2-steroids
Tools that simplify and speed up the work, programming and debugging sites on Magento 2

## 1. How to Install

1. Goto Magento 2 root folder
2. Download and extract magento-2-steroids arhive

```
curl -L https://github.com/rhoni/magento-2-steroids/archive/master.tar.gz | tar xz
mv magento-2-steroids-master/* .
rmdir magento-2-steroids-master

```

## 2. List of commands

* ./c
```
php bin/magento cache:clean
```

* ./f
```
php bin/magento cache:flush
```

* ./cf
```
php bin/magento cache:clean
php bin/magento cache:flush
```

* ./modules
```
php bin/magento module:status
```

* ./upgrade
```
php bin/magento setup:upgrade
```

* ./compile
```
php bin/magento setup:di:compile
```

...
