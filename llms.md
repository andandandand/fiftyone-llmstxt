Table of Contents

- [Docs](https://docs.voxel51.com/#) >

- FiftyOne

Contents


# FiftyOne [Anchor](https://docs.voxel51.com/\#fiftyone)

**The open-source tool for building high-quality datasets and computer vision models**

Nothing hinders the success of machine learning systems more than poor quality
data. And without the right tools, improving a model can be time-consuming and
inefficient.

FiftyOne supercharges your machine learning workflows by enabling you to
visualize datasets and interpret models faster and more effectively.

Improving data quality and understanding your model’s failure modes are the
most impactful ways to boost the performance of your model.

FiftyOne provides the building blocks for optimizing your dataset analysis
pipeline. Use it to get hands-on with your data, including visualizing complex
labels, evaluating your models, exploring scenarios of interest, identifying
failure modes, finding annotation mistakes, and much more!

[Install FiftyOne!](https://docs.voxel51.com/getting_started/install.html)

FiftyOne integrates naturally with your favorite tools. Click on a logo to
learn how:

[![PyTorch](https://voxel51.com/images/integrations/pytorch-128.png)](https://docs.voxel51.com/recipes/adding_detections.html "PyTorch")

[![PyTorch Lightning](https://voxel51.com/images/integrations/pytorch-lightning-128.png)](https://docs.voxel51.com/integrations/lightning_flash.html "PyTorch Lightning")

[![Hugging Face](https://voxel51.com/images/integrations/hugging-face-128.png)](https://docs.voxel51.com/integrations/huggingface.html "Hugging Face")

[![Ultralytics](https://voxel51.com/images/integrations/ultralytics-128.png)](https://docs.voxel51.com/integrations/ultralytics.html "Ultralytics")

[![SuperGradients](https://voxel51.com/images/integrations/super-gradients-128.png)](https://docs.voxel51.com/integrations/super_gradients.html "SuperGradients")

[![TensorFlow](https://voxel51.com/images/integrations/tensorflow-128.png)](https://docs.voxel51.com/recipes/adding_detections.html "TensorFlow")

[![Detectron2](https://voxel51.com/images/integrations/detectron2-128.png)](https://docs.voxel51.com/tutorials/detectron2.html "Detectron2")

[![Qdrant](https://voxel51.com/images/integrations/qdrant-128.png)](https://docs.voxel51.com/integrations/qdrant.html "Qdrant")

[![Redis](https://voxel51.com/images/integrations/redis-128.png)](https://docs.voxel51.com/integrations/redis.html "Redis")

[![Pinecone](https://voxel51.com/images/integrations/pinecone-128.png)](https://docs.voxel51.com/integrations/pinecone.html "Pinecone")

[![MongoDB](https://voxel51.com/images/integrations/mongodb-128.png)](https://docs.voxel51.com/integrations/mongodb.html "MongoDB")

[![Elasticsearch](https://voxel51.com/images/integrations/elasticsearch-128.png)](https://docs.voxel51.com/integrations/elasticsearch.html "Elasticsearch")

[![Milvus](https://voxel51.com/images/integrations/milvus-128.png)](https://docs.voxel51.com/integrations/milvus.html "Milvus")

[![LanceDB](https://voxel51.com/images/integrations/lancedb-128.png)](https://docs.voxel51.com/integrations/lancedb.html "LanceDB")

[![ActivityNet](https://voxel51.com/images/integrations/activitynet-128.png)](https://docs.voxel51.com/integrations/activitynet.html "ActivityNet")

[![COCO](https://voxel51.com/images/integrations/coco-128.png)](https://docs.voxel51.com/integrations/coco.html "COCO")

[![Open Images](https://voxel51.com/images/integrations/open-images-128.png)](https://docs.voxel51.com/integrations/open_images.html "Open Images")

[![Jupyter](https://voxel51.com/images/integrations/jupyter-128.png)](https://docs.voxel51.com/environments/index.html#notebooks "Jupyter")

[![Google Colab](https://voxel51.com/images/integrations/colab-128.png)](https://docs.voxel51.com/environments/index.html#notebooks "Google Colab")

[![Plotly](https://voxel51.com/images/integrations/plotly-128.png)](https://docs.voxel51.com/user_guide/plots.html "Plotly")

[![CVAT](https://voxel51.com/images/integrations/cvat-128.png)](https://docs.voxel51.com/integrations/cvat.html "CVAT")

[![Label Studio](https://voxel51.com/images/integrations/labelstudio-128.png)](https://docs.voxel51.com/integrations/labelstudio.html "Label Studio")

[![V7](https://voxel51.com/images/integrations/v7-128.png)](https://docs.voxel51.com/integrations/v7.html "V7")

[![Segments](https://voxel51.com/images/integrations/segments-128.png)](https://github.com/segments-ai/segments-voxel51-plugin "Segments")

[![Labelbox](https://voxel51.com/images/integrations/labelbox-128.png)](https://docs.voxel51.com/integrations/labelbox.html "Labelbox")

[![Scale AI](https://voxel51.com/images/integrations/scale-128.png)](https://docs.voxel51.com/api/fiftyone.utils.scale.html "Scale AI")

[![Google Cloud](https://voxel51.com/images/integrations/google-cloud-128.png)](https://docs.voxel51.com/teams/installation.html#google-cloud-storage "Google Cloud")

[![Amazon Web Services](https://voxel51.com/images/integrations/aws-128.png)](https://docs.voxel51.com/teams/installation.html#amazon-s3 "Amazon Web Services")

[![Azure](https://voxel51.com/images/integrations/azure-128.png)](https://docs.voxel51.com/teams/installation.html#microsoft-azure "Azure")

Note

FiftyOne is growing!
[Sign up for the mailing list](https://share.hsforms.com/1zpJ60ggaQtOoVeBqIZdaaA2ykyk)
to learn about new features as they come out.

## Core Capabilities [Anchor](https://docs.voxel51.com/\#core-capabilities)

### Curating datasets

Surveys show that machine learning engineers spend over half of their time wrangling data, but it doesn't have to be that way. Use FiftyOne's powerful dataset import and manipulation capabilities to manage your data with ease.

[Learn how to load data into FiftyOne](https://docs.voxel51.com/user_guide/dataset_creation/index.html)

![](https://docs.voxel51.com/_static/images/homepage_curate.gif)

### Evaluating models

Aggregate metrics alone don’t give you the full picture of your ML models. In practice, the limiting factor on your model’s performance is often data quality issues that you need to see to address. FiftyOne makes it easy to do just that.

[See how to evaluate models with FiftyOne](https://docs.voxel51.com/tutorials/evaluate_detections.html)

![](https://docs.voxel51.com/_static/images/homepage_evaluate.gif)

### Visualizing embeddings

Are you using embeddings to analyze your data and models? Use FiftyOne's embeddings visualization capabilities to reveal hidden structure in you data, mine hard samples, pre-annotate data, recommend new samples for annotation, and more.

[Experience the power of embeddings](https://docs.voxel51.com/tutorials/image_embeddings.html)

![](https://docs.voxel51.com/_static/images/homepage_embeddings.gif)

### Working with geolocation

Many datasets have location metadata, but visualizing location-based datasets has traditionally required closed source or cloud-based tools. FiftyOne provides native support for storing, visualizing, and querying datasets by location.

[Visualize your location data](https://docs.voxel51.com/user_guide/plots.html#geolocation-plots)

![](https://docs.voxel51.com/_static/images/homepage_location.gif)

### Finding annotation mistakes

Annotations mistakes create an artificial ceiling on the performance of your model. However, finding these mistakes by hand is not feasible! Use FiftyOne to automatically identify possible label mistakes in your datasets.

[Check out the label mistakes tutorial](https://docs.voxel51.com/tutorials/classification_mistakes.html)

![](https://docs.voxel51.com/_static/images/homepage_mistakes.gif)

### Removing redundant images

During model training, the best results will be seen when training on unique data. Use FiftyOne to automatically remove duplicate or near-duplicate images from your datasets and curate diverse training datasets from your raw data.

[Try the image uniqueness tutorial](https://docs.voxel51.com/tutorials/uniqueness.html)

![](https://docs.voxel51.com/_static/images/homepage_redundant.gif)

## Core Concepts [Anchor](https://docs.voxel51.com/\#core-concepts)

### FiftyOne Library [Anchor](https://docs.voxel51.com/\#fiftyone-library)

FiftyOne’s core library provides a structured yet dynamic representation to
explore your datasets. You can efficiently query and manipulate your dataset by
adding custom tags, model predictions and more.

[Explore the library](https://docs.voxel51.com/user_guide/basics.html)

|     |     |
| --- | --- |
| ```<br> 1<br> 2<br> 3<br> 4<br> 5<br> 6<br> 7<br> 8<br> 9<br>10<br>11<br>12<br>13<br>14<br>```<br>![Copy to clipboard](https://docs.voxel51.com/_static/copy-button.svg) | ```<br>import fiftyone as fo<br>dataset = fo.Dataset("my_dataset")<br>sample = fo.Sample(filepath="/path/to/image.png")<br>sample.tags.append("train")<br>sample["custom_field"] = 51<br>dataset.add_sample(sample)<br>view = dataset.match_tags("train").sort_by("custom_field").limit(10)<br>for sample in view:<br>    print(sample)<br>```<br>![Copy to clipboard](https://docs.voxel51.com/_static/copy-button.svg) |

Note

FiftyOne is designed to be lightweight and flexible, making it easy to load
your datasets. FiftyOne supports loading datasets in a variety of common
formats out-of-the-box, and it also provides the extensibility to load
datasets in custom formats.

Check out [loading datasets](https://docs.voxel51.com/user_guide/dataset_creation/index.html) to see
how to load your data into FiftyOne.

### FiftyOne App [Anchor](https://docs.voxel51.com/\#fiftyone-app)

The FiftyOne App is a graphical user interface that makes it easy to explore
and rapidly gain intuition into your datasets. You can visualize labels like
bounding boxes and segmentations overlaid on the samples; sort, query and
slice your dataset into any subset of interest; and more.

[See more of the App](https://docs.voxel51.com/user_guide/app.html)

![fiftyone-app](https://docs.voxel51.com/_images/homepage_app.png)

### FiftyOne Brain [Anchor](https://docs.voxel51.com/\#fiftyone-brain)

The FiftyOne Brain is a library of powerful machine learning-powered
capabilities that provide insights into your datasets and recommend ways to
modify your datasets that will lead to measurably better performance of your
models.

[Learn more about the Brain](https://docs.voxel51.com/brain.html)

|     |     |
| --- | --- |
| ```<br>1<br>2<br>3<br>4<br>```<br>![Copy to clipboard](https://docs.voxel51.com/_static/copy-button.svg) | ```<br>import fiftyone.brain as fob<br>fob.compute_uniqueness(dataset)<br>rank_view = dataset.sort_by("uniqueness")<br>```<br>![Copy to clipboard](https://docs.voxel51.com/_static/copy-button.svg) |

### FiftyOne Plugins [Anchor](https://docs.voxel51.com/\#fiftyone-plugins)

FiftyOne provides a powerful plugin framework that allows for extending and
customizing the functionality of the tool to suit your specific needs.

With plugins, you can add new functionality to the FiftyOne App, create
integrations with other tools and APIs, render custom panels, and add custom
buttons to menus.

With [FiftyOne Teams](https://docs.voxel51.com/teams/teams_plugins.html#teams-delegated-operations), you can even write
plugins that allow users to execute long-running tasks from within the App that
run on a connected compute cluster.

[Install some plugins!](https://docs.voxel51.com/plugins/index.html)

![fiftyone-plugins](https://docs.voxel51.com/_images/embeddings.gif)

### Dataset Zoo [Anchor](https://docs.voxel51.com/\#dataset-zoo)

The FiftyOne Dataset Zoo provides a powerful interface for downloading datasets
and loading them into FiftyOne.

It provides native access to dozens of popular benchmark datasets, and it als
supports downloading arbitrary public or private datasets whose
download/preparation methods are provided via GitHub repositories or URLs.

[Check out the Dataset Zoo](https://docs.voxel51.com/dataset_zoo/index.html)

|     |     |
| --- | --- |
| ```<br>1<br>2<br>3<br>4<br>5<br>6<br>```<br>![Copy to clipboard](https://docs.voxel51.com/_static/copy-button.svg) | ```<br> import fiftyone as fo<br> import fiftyone.zoo as foz<br> dataset = foz.load_zoo_dataset("coco-2017", split="validation")<br> session = fo.launch_app(dataset)<br>```<br>![Copy to clipboard](https://docs.voxel51.com/_static/copy-button.svg) |

![dataset-zoo](https://docs.voxel51.com/_images/dataset_zoo_coco_2017.png)

### Model Zoo [Anchor](https://docs.voxel51.com/\#model-zoo)

The FiftyOne Model Zoo provides a powerful interface for downloading models and
applying them to your FiftyOne datasets.

It provides native access to hundreds of pre-trained models, and it also
supports downloading arbitrary public or private models whose definitions are
provided via GitHub repositories or URLs.

[Check out the Model Zoo](https://docs.voxel51.com/model_zoo/index.html)

|     |     |
| --- | --- |
| ```<br> 1<br> 2<br> 3<br> 4<br> 5<br> 6<br> 7<br> 8<br> 9<br>10<br>11<br>12<br>13<br>14<br>15<br>16<br>17<br>18<br>19<br>```<br>![Copy to clipboard](https://docs.voxel51.com/_static/copy-button.svg) | ```<br> import fiftyone as fo<br> import fiftyone.zoo as foz<br> dataset = foz.load_zoo_dataset(<br>     "coco-2017",<br>     split="validation",<br>     max_samples=50,<br>     shuffle=True,<br> )<br> model = foz.load_zoo_model(<br>     "clip-vit-base32-torch",<br>     text_prompt="A photo of a",<br>     classes=["person", "dog", "cat", "bird", "car", "tree", "chair"],<br> )<br> dataset.apply_model(model, label_field="zero_shot_predictions")<br> session = fo.launch_app(dataset)<br>```<br>![Copy to clipboard](https://docs.voxel51.com/_static/copy-button.svg) |

## What’s Next? [Anchor](https://docs.voxel51.com/\#what-s-next)

Where should you go from here? You could…

- [Install FiftyOne](https://docs.voxel51.com/getting_started/install.html#installing-fiftyone)

- Try one of the [tutorials](https://docs.voxel51.com/tutorials/index.html) that demonstrate the unique
capabilities of FiftyOne

- Explore [recipes](https://docs.voxel51.com/recipes/index.html) for integrating FiftyOne into
your current ML workflows

- Check out the [cheat sheets](https://docs.voxel51.com/cheat_sheets/index.html) for topics you may
want to master quickly

- Consult the [user guide](https://docs.voxel51.com/user_guide/index.html) for detailed instructions on
how to accomplish various tasks with FiftyOne


## Need Support? [Anchor](https://docs.voxel51.com/\#need-support)

If you run into any issues with FiftyOne or have any burning questions, feel
free to [connect with us on Discord](https://community.voxel51.com/) or reach out to
us at [support@voxel51.com](mailto:support%40voxel51.com).

- [FiftyOne](https://docs.voxel51.com/#)
  - [Core Capabilities](https://docs.voxel51.com/#core-capabilities)
  - [Core Concepts](https://docs.voxel51.com/#core-concepts)
    - [FiftyOne Library](https://docs.voxel51.com/#fiftyone-library)
    - [FiftyOne App](https://docs.voxel51.com/#fiftyone-app)
    - [FiftyOne Brain](https://docs.voxel51.com/#fiftyone-brain)
    - [FiftyOne Plugins](https://docs.voxel51.com/#fiftyone-plugins)
    - [Dataset Zoo](https://docs.voxel51.com/#dataset-zoo)
    - [Model Zoo](https://docs.voxel51.com/#model-zoo)
  - [What’s Next?](https://docs.voxel51.com/#what-s-next)
  - [Need Support?](https://docs.voxel51.com/#need-support)

[iframe](https://reflex.bigpicture.io/event-store)