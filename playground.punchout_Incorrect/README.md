# Fact Capsule

Welcome to your Fact capsule!  The next steps you should take are:

1. Add Training. You might want to add additional training examples for recognizing specific types of facts.

2. Have fun!

# Try it out

[Use the simulator](https://bixbydevelopers.com/dev/docs/dev-guide/developers/ide.simulator) to run the following:

`[g:GetContent] Tell me a fact`

## Customize Your Capsule

### Add Your Own Content

If you are not linking to images hosted externally, then the local images must be in your `assets/images` folder. You can sort these images into further subfolders, if necessary. For example, if you have animal and plant images, you might want to place all your animal images in one folder and all your plant images into another. You can place them under `assets/images/animals` and `assets/images/plants` respectively. You would then refer to each image URL as something like `images/plants/tulip.png`.

If your content can be accessed through an API instead, you could choose not to use the `content.js` file and instead [Call a Web Service](https://bixbydevelopers.com/dev/docs/dev-guide/developers/actions.js-actions#calling-web-services) to return a JSON object that contains your material. However, you might have to change the existing modeling action implementations to process this and you might be better off [creating a new capsule](https://bixbydevelopers.com/dev/docs/dev-guide/developers/managing-caps.planning-external).

### Add and Update Training

We provide several training entries with this template. In order for Bixby to understand and properly reply to user requests for your capsule, you need to [add additional training examples](https://bixbydevelopers.com/dev/docs/dev-guide/developers/training.intro-training#creating-training-examples-using-the-training-tool). You should pay particular attention to adding a few examples with tags that match your content.

Also remove any training entries that are not relevant to your capsule. For example, if you are creating a capsule about plant facts, you should remove all the entries that tags things other than plants. Your training examples should only be related to your content.

## Submitting Your Capsule to the Marketplace

Learn about submitting your capsule to the [Marketplace](https://bixbydevelopers.com/dev/docs/dev-guide/developers/deploying.can-submission#about-the-marketplace)

---

## Additional Resources

### Your Source for Everything Bixby

* [Bixby Developer Center](https://bixbydevelopers.com) - Everything you need to get started with Bixby Development!

### Guides & Best Practices

* [Quick Start Guide](https://bixbydevelopers.com/dev/docs/get-started/quick-start) - Build your first capsule
* [Design Guides](https://bixbydevelopers.com/dev/docs/dev-guide/design-guides) - Best practices for designing your capsules
* [Developer Guides](https://bixbydevelopers.com/dev/docs/dev-guide/developers) - Guides that take you from design and modeling all the way through deployment of your capsules

### Video Guides

* [Introduction to Bixby](https://youtu.be/DFvpK4PosvI) - Bixby and the New Exponential Frontier of Intelligent Assistants
* [Bixby Fundamentals](https://bixby.developer.samsung.com/newsroom/en-us/22/01/2019/Teaching-Bixby-Fundamentals-What-You-Need-to-Know) - Bixby Fundamentals: What You Need to Know

### Need Support?

* Have a feature request? Please suggest it in our [Support Community](https://support.bixbydevelopers.com/hc/en-us/community/topics/360000183273-Feature-Requests) to help us prioritize.
* Have a technical question? Ask on [Stack Overflow](https://stackoverflow.com/questions/tagged/bixby) with tag “bixby”
