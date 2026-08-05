# Field Label Override

## Table of contents

 - Introduction
 - Requirements
 - Installation
 - Configuration
 - Maintainers

## Introduction

**Field Label Override** allows administrators to set custom labels to fields per entity view mode. This module works with fields for any entity type, such as nodes, taxonomy terms, blocks, etc.

Example: The content type *Article* has the field **Body**. Using this module, it is possible to set the label of this field to be displayed as **Full Description** for the *Default (Full)* view mode, where the full content of the field is rendered, and **Short Description** for the *Teaser* view mode, where only a summary or a trimmed version of the content is presented.

## Requirements

This module requires Drupal core >= 10.1.

## Installation

Install as you would normally install a contributed Drupal module.
Visit https://www.drupal.org/node/1897420 for further information.

## Configuration

This module includes two settings:

**Override label**: The label to be used for the field in that respective view mode.

**Preserve original label**: Checkbox to determine if the original field label will be preserved. If checked, the original label will not be changed, and a new variable `label_override` will be available in the field twig template, containin the custom label. If unchecked, the original `label` will be completely overridden by the custom label.

## Maintainers

Current maintainers:
- Mauricio Silveira ([maursilveira](https://www.drupal.org/u/maursilveira))
