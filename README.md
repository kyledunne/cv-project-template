# Computer Vision Project Template Notebook

This is a base project you can clone to quickly get a PyTorch computer vision project up and running using Lightning.

[notebook.ipynb](notebook.ipynb) contains:

- `DataConfig` class, for specifying where your dataset lives
- `TrainConfig` class, for specifying hyperparameters and other training configuration settings
- `TemplateDataset` class: template subclass of `torch.utils.data.Dataset`
- `TemplateDataModule` class: template subclass of `lightning.pytorch.LightningDataModule`
- `TemplateLightningModule` class: template subclass of `lightning.pytorch.LightningModule`
- Template code for creating and fitting a `lightning.pytorch.Trainer`