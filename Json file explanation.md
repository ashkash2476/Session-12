# Session-12

JSON file - Annotation data for first file
'images': [{'date_captured': '', 'file_name': '1.jpeg', 'height': 183, 'id': 1, 'license': 0, 'width': 275},

'annotations': [{'area': 18447, 'bbox': [62, 34, 143, 129], 'category_id': 4, 'id': 1, 'image_id': 1, 'iscrowd': 0, 'segmentation': [[62, 34, 205, 34, 205, 163, 62, 163]]},

Explanation - Important terms -
In 'images' key : 1) width - The actual width of the image on which the annotation is done - 421

2) height - The actual height of the image on which the annotation is done - 499

3) file_name - name of the image as in folder. (dog.4001.jpg)

In 'annotations' key

1) bbox - [107, 56, 221, 437], 1) 107, 56 - These are the centre coordinates for the bounding box. 107 - x and 56 - y

2) 221,437 - These are the width and height respective to bbox. Width=221, Height = 437
