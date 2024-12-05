# Building a custom image picker for Stencil's Form integration

## Running the example

```
python -m http.server 8000
```

This will run the example at [http://localhost:8000](http://localhost:8000). This example __must__ be run at localhost listening to port 8000.

## How it works

When you click on the `Choose image` inside the form, it sends an event to the parent window in which you can act upon the received message.

From here, you can build your own custom image picker like getting the image from S3 or any API.

Then, you just need to send a new event to the iframe containing the form to update the selected image.

![Diagram](https://i.ibb.co/dr59LVG/image.png)

## Documentation

TBA
