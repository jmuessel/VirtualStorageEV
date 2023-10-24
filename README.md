# VirtualStorageEV
This repo allows to model indivual EV-flexibility profiles and aggregate them accurately (no naive aggregation).
Furthermore, it allows to determine a representative fleet-size using peak-load as an indicator.
The code has been used for the publication: 
```Muessel, J., Ruhnau, O., Madlener, R., 2023. Accurate and scalable representation of electric vehicles in energy system models: A virtual storage-based aggregation approach. iScience. DOI: 10.1016/j.isci.2023.107816```

# Repo structure
```Aggregation```: ```Virtual_Storage_Algorithm.ipynb```allows to create and aggregate individual flexibility potentials.
```Emobpy```: The input data for the profiles was created using [emobpy](https://pypi.org/project/emobpy/) with the notebook ```Emobpy/my_emobpy
/Generation.ipynb```

## License
A patent application for the virtual storage approach is pending (DE102023102589.9). Please contact the authors if you want to use it.



