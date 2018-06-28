# Ansible Lightbulb

The Ansible Lightbulb project is an effort to provide a content toolkit and educational reference for effectively communicating and teaching Ansible topics.

Lightbulb began life as the content that supported Ansible's training program before it joined the Red Hat family focused solely on Linux server automation.

This content is now taking on a new life as a multi-purpose toolkit for effectively demonstrating Ansible's capabilities or providing informal workshop training in various forms -- instructor-led, hands-on or self-paced.

Over time Lightbulb will be expanded to include advanced and developer topics in addition to expanding beyond linux server automation and into Windows and network automation.

## What's Provided

The Ansible Lightbulb project has been designed to be used as a toolkit and best practices reference for Ansible presentations ranging from demos thru self-paced learning thru hands-on workshops. Here you will find:

* Examples
* Presentation Decks
* Guides
* Facilitator Documentation

### Examples

The content in `examples/` is the heart of what Lightbulb has to offer. They are complete Ansible playbooks that demonstrate the most fundamental features and most common use patterns.

These examples are an excellent educational reference for communicating how Ansible works in a clear, focused and consistent manner using recommended best practices.

This content is a great source for canned demos or something you can walk-thru to illustrate automating with Ansible to a group. Some of the examples  serve as the solutions to the workshops.


### Presentation Decks

The content of `decks/` are collection of presentation decks using the [reveal.js framework](http://lab.hakim.se/reveal-js/) for delivering presentations.

### Guides

The `guides/` provide closely guided exercises with a lower barrier to entry. These are suitable for beginners or larger audiences. People can follow the guides on their own pace, and usually need very limited support is required during the execution of such labs.

### Lab Provisioner

**Coming Soon.** Vagrant support for self-paced learning is planned. Legacy support from the previous generation of Lightbulb remains, but is in need of an overhaul.

### Facilitator Documentation

`facilitator/` includes documentation on recommended ways Lightbulb content can be assembled and used for a wide range of purposes and scenarios.

If you are planning on using Lightbulb for some sort of informal training on automating with Ansible [this documentation](facilitator/README.md) should be your next stop.

## Requirements

True to its philosophy and The Ansible Way, Lightbulb has been developed so that using Lightbulb is as simple and low-overhead as possible. Requirements depend on the format and delivery of the Lightbulb content.

* Modern HTML5 Standard Compliant Web Browser
* A recent stable version of Python 2.7 
* The latest stable versions of Ansible.
* A SSH client such as PuTTY or Mac OSX Terminal.

## Assumed Knowledge

For hands-on or self-paced training, students should have working knowledge of using SSH and command line shell (BASH). The ability to SSH from their personal laptop to a lab environment hosted in a public cloud can also be required based on the format and presentation of the context.

For demos and instructor-led exercises, conceptual understanding of linux system admin, DevOps and distributed application architecture is all that is required.

## Reference

* [Ansible Documentation](http://docs.ansible.com)
* [Ansible Best Practices: The Essentials](https://www.ansible.com/blog/ansible-best-practices-essentials)

## License

Red Hat, the Shadowman logo, Ansible, and Ansible Tower are trademarks or registered trademarks of Red Hat, Inc. or its subsidiaries in the United States and other countries. 

All other parts of Ansible Lightbulb are made available under the terms of the [MIT License](LICENSE).
