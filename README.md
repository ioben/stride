# A Markdown Slide Deck generator for Rust
This slide generator is specifically created for rust:

- You can embed Rust code in a slide and run them right from the slide.
- Slides are generated by ``rustdoc``. So no new software required to build the slides.

This project is based on https://github.com/HackEPFL/rust-workshop-slides.git.

# Getting Started
## Installation Guide
Install Rust by following the [official guide](http://doc.rust-lang.org/guide.html#installing-rust) if you have not already done so.

Clone all the required repos:

```bash
git clone https://github.com/bibhas2/stride
cd stride
git clone https://github.com/ajaxorg/ace-builds.git
```

**Important:** Make sure that you clone ``ace-builds`` inside of the ``stride`` folder.

## Verify Installation
You can build the sample presentation file to see if everything is in order.

From the ``stride`` folder, run:

```bash
./build.sh slides.md
```

Open the resulting ``slides.html`` in a modern browser. You should be able to use arrow keys to navigate through the slides. You should be able to execute embdded code by clicking the **Run** button.

