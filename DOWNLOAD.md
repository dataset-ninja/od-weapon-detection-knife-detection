Dataset **OD-WeaponDetection: Knife Detection** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogInMzOi8vc3VwZXJ2aXNlbHktZGF0YXNldHMvMjc5Nl9PRC1XZWFwb25EZXRlY3Rpb246IEtuaWZlIERldGVjdGlvbi9vZC13ZWFwb25kZXRlY3Rpb246LWtuaWZlLWRldGVjdGlvbi1EYXRhc2V0TmluamEudGFyIiwgInNpZyI6ICJ5WHQ5bUtCcEc3Z2hXN1ViOUVkSEQ5OWtZZGpQSm1kcDRVeG04S3czbEJFPSJ9?response-content-disposition=attachment%3B%20filename%3D%22od-weapondetection%3A-knife-detection-DatasetNinja.tar%22)

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

The data in original format can be [downloaded here](https://drive.google.com/file/d/1Szc920DAh5kU8Qk38Doq0znEVR1QmTZS/view?usp=sharing).