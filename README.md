# Singularity config for biotools container

A [Singularity Hub](https://www.singularity-hub.org/) definition for learning purposes.
An associated tutorial on genomics can be found at [http://reproducible.sschmeier.com](http://reproducible.sschmeier.com).

If [Singularity](http://singularity.lbl.gov) is installed locally, the container can be build (needs root access) locally like this:

```bash
sudo singularity build biotools.simg Singularity
```

The container can alos be downloaded from [Singularity Hub](https://www.singularity-hub.org/) without root access to the local machine like this:

```bash
singularity pull sschmeier/biotools:latest 
```

However, we will be using the contianer straight from [Singularity Hub](https://www.singularity-hub.org/) in a workflow.
