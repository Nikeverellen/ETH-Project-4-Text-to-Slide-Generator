# ETH-Project-4-Text-to-Slide-Generator
In this project you will implement a system which, when provided a text as input, generates the content of a slide deck. The project covers a number of machine learning techniques. We learn how to use sentence embeddings for summarizing texts, how to generate summaries with language models, and how to retrieve or generate images using textual image descriptions.

The structure of the project is as follows.

    Slide text. First, given a text that describes, possibly at length, the desired content of the slide deck, we will obtain a short list of summary sentences. These sentences are the bullet points that appear on the slides. To obtain summary sentences, you will implement abstractive summarization. In abstractive summarization techniques, summary sentences are generated (i.e., they need not, and often are not, present verbatim in the original text). You will use zero-shot and few-shot prompting (in-context learning) to have a language model generate summary sentences.

    Slide images. The second part of the project involves obtaining images that match the textual content of the slides. You will use two techniques, image retrieval and text-to-image generation.

    For the image retrieval solution, you will use a multimodal model to embed both text queries and images (we'll take them from a public database) into a shared semantic space. To select the right image for a slide, you will pick the one that is closest to keywords in the slide text.
    For the image generation approach, you will use a slightly different type of multimodal model with generative capabilities. Given the keywords in the slide text, it generates images from scratch.
