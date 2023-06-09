Examples for the Neuroscience External Resources Data Standard (NERD)
=====================================================================

In a time where large swaths of digital assets are being stored in data repositories, e.g., DANDI, 
it has become increasingly important to have a standardized method to attach contextual metadata in 
order to relate datasets. Given the complex nature and the expansive scope of neuroscience datasets, 
having this system to create and maintain precise metadata will allow researchers to more easily query, 
reuse, and analyze data; data that follow the FAIR principles. To address this crucial issue, we 
present the Neuroscience External Resources Data (NERD) standard, enabling users to annotate new and 
existing datasets by mapping external references to the data without requiring modification of the 
original dataset. We integrate NERD closely with NWB, an existing and widely used data standard for 
sharing and storing neurophysiology data, to facilitate adoption through integration with an established 
data ecosystem, while also giving users a deep set of tools to more easily create and manage data in 
compliance with controlled term sets.

This repository hosts examples, tutorials, and the in-development publication of NERD.

Installation
============
To run the tutorials, first install the latest versions of PyNWB and HDMF:

```bash
pip install -U pynwb hdmf
```

API Documentation
=================
To learn more about the Python API for NWB (PyNWB) and the Hierarchical Data Modeling Framework (HDMF), 
which support NERD, see the [PyNWB documentation](https://pynwb.readthedocs.io/en/stable/) and the 
[HDMF documentation](https://hdmf.readthedocs.io/en/stable/).
