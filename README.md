# Django Hyper Editor

Django integration for [Hyper Editor](https://django-hyper-editor.readthedocs.io/en/latest/).


## Installation

Install via pip

```sybase
pip install hypereditor
```

Add to ``settings.py``
```python
INSTALLED_APPS = [
    ...
    'hypereditor'
]
```

Add to ``urls.py``
```python
urlpatterns = [
    ...
    path('hypereditor/', include('hypereditor.urls')),
]
```

## Documentation

Please check the documentation site - [https://divineitlimited.github.io/django-hyper-editor](https://divineitlimited.github.io/django-hyper-editor)

## TODO
- [x] Hyper Editor Output Parser
- [x] Block System
- [x] Create simple block without using js
- [x] Django Model Integration ``HyperField``
- [x] Django Admin Integration
- [x] Django Form Integration
- [x] Wagtail Integration ``HyperFieldPanel``
- [x] Template tag for preview and render
- [x] Documentation
- [ ] Media Handling
