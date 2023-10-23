Dataset **OD-WeaponDetection: Knife Detection** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/D/4/00/vZS9zzZgfMZi50tQUWMVQy3gJ3zm79Q2XHIFDOckcEuWX3ZWdXr89q8ZLOc0VeifPiW5QG5t6eGPG9Kjr88erof8aKVFQudXlmWWcOmH9kXZaNoGUwrQ2C484VAF.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='OD-WeaponDetection: Knife Detection', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

