# COCO Manager
This repo will include various Python scripts to manage COCO datasets.

For now, the following functionality is available and applies to the Object Detection annotation format. Learn more here: http://cocodataset.org/#format-data

## Filter
filter.py allows you to filter an existing COCO Instances JSON file by categories.

The following command will filter the input instances json to only include images and annotations for the categories person, dog, or cat:
```python filter.py --input_json c:\users\you\annotations\instances_train2017.json --output_json c:\users\you\annotations\filtered.json --categories person dog cat```

Note: This isn't looking for images with all categories in one. It includes images that have at least one of the specified categories.

# Immersive Limit Resources
For more helpful resources, please check out https://www.immersivelimit.com/tutorials.