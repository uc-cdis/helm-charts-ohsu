> [!NOTE]
> Adapted from the [Gen3 Helm Charts repo](https://github.com/uc-cdis/gen3-helm) from the [Center for Translational Data Science](https://github.com/uc-cdis)

# Helm Charts 📚

Helm charts for deploying various projects on any kubernetes cluster.

## TL;DR ⚡
```
helm repo add garage https://ohsu-comp-bio.github.io/helm-charts
helm repo update
helm upgrade --install ohsu funnel -f ./values.yaml 
```

# Programs 💻 

| Program | Description |
:--------:|:------------:
<a href="https://bmeg.github.io/grip/"><img width="50%" src="https://github.com/user-attachments/assets/64363c84-ecc6-4de5-8380-4d4f2f2c9ef9"/></a> | [**GRIP**](https://github.com/bmeg/grip) <br> GRIP stands for GRaph Integration Platform. It provides a graph interface on top of a variety of existing database technologies including: MongoDB, Elasticsearch, PostgreSQL, MySQL, MariaDB, Badger, and LevelDB.
<a href="https://ohsu-comp-bio.github.io/funnel/"><img width="50%" src="https://github.com/user-attachments/assets/f51cf06b-d802-4e20-bde1-bcd1fc5657e6"/><a/> | [**Funnel**](https://github.com/ohsu-comp-bio/funnel) <br> Funnel is a toolkit for distributed, batch task execution, including a server, worker, and a set of compute, storage, and database backends.

## GRIP 🔧

```
helm upgrade --install ohsu funnel -f ./values.yaml 
```

## Funnel 🌪️️

```
helm upgrade --install ohsu funnel -f ./values.yaml 
```
