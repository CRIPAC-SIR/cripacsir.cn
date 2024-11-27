---
title: Light Field Photography
#summary: An example of linking directly to an external project website using `external_link`.
summary: Light field is a parameterized representation of four-dimensional radiation field which contains both position and direction information in space
tags:
- Light Field Photography
date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: 

image:
  caption: Lytro Illum 2nd generation light field camera.
  focal_point: Smart
---

## Light field

The light field is a vector function that describes the amount of light flowing in every direction through every point in space. The space of all possible light rays is given by the five-dimensional plenoptic function, and the magnitude of each ray is given by the radiance. Michael Faraday was the first to propose (in an 1846 lecture entitled "Thoughts on Ray Vibrations") that light should be interpreted as a field, much like the magnetic fields on which he had been working for several years. The phrase light field was coined by Andrey Gershun in a classic paper on the radiometric properties of light in three-dimensional space (1936).

## The 4D light field

In a plenoptic function, if the region of interest contains a concave object (think of a cupped hand), then light leaving one point on the object may travel only a short distance before being blocked by another point on the object. No practical device could measure the function in such a region.

However, if we restrict ourselves to locations outside the convex hull (think shrink-wrap) of the object, i.e. in free space, then we can measure the plenoptic function by taking many photos using a digital camera. Moreover, in this case the function contains redundant information, because the radiance along a ray remains constant from point to point along its length, as shown at left. In fact, the redundant information is exactly one dimension, leaving us with a four-dimensional function (that is, a function of points in a particular four-dimensional manifold). Parry Moon dubbed this function the photic field (1981), while researchers in computer graphics call it the 4D light field (Levoy 1996) or Lumigraph (Gortler 1996). Formally, the 4D light field is defined as radiance along rays in empty space.

The set of rays in a light field can be parameterized in a variety of ways, a few of which are shown below. Of these, the most common is the two-plane parameterization shown at right (below). While this parameterization cannot represent all rays, for example rays parallel to the two planes if the planes are parallel to each other, it has the advantage of relating closely to the analytic geometry of perspective imaging. Indeed, a simple way to think about a two-plane light field is as a collection of perspective images of the st plane (and any objects that may lie astride or beyond it), each taken from an observer position on the uv plane. A light field parameterized this way is sometimes called a light slab.

## Ways to create light fields

Light fields are a fundamental representation for light. As such, there are as many ways of creating light fields as there are computer programs capable of creating images or instruments capable of capturing them.

In computer graphics, light fields are typically produced either by rendering a 3D model or by photographing a real scene. In either case, to produce a light field views must be obtained for a large collection of viewpoints. Depending on the parameterization employed, this collection will typically span some portion of a line, circle, plane, sphere, or other shape, although unstructured collections of viewpoints are also possible (Buehler 2001).

Devices for capturing light fields photographically may include a moving handheld camera or a robotically controlled camera (Levoy 2002), an arc of cameras (as in the bullet time effect used in The Matrix), a dense array of cameras (Kanade 1998; Yang 2002; Wilburn 2005), handheld cameras (Ng 2005; Georgiev 2006; Marwah 2013), microscopes (Levoy 2006), or other optical system (Bolles 1987).

How many images should be in a light field? The largest known light field (of Michelangelo's statue of Night) contains 24,000 1.3-megapixel images. At a deeper level, the answer depends on the application. For light field rendering (see the Application section below), if you want to walk completely around an opaque object, then of course you need to photograph its back side. Less obviously, if you want to walk close to the object, and the object lies astride the st plane, then you need images taken at finely spaced positions on the uv plane (in the two-plane parameterization shown above), which is now behind you, and these images need to have high spatial resolution.

The number and arrangement of images in a light field, and the resolution of each image, are together called the "sampling" of the 4D light field. Analyses of light field sampling have been undertaken by many researchers; a good starting point is Chai (2000). Also of interest is Durand (2005) for the effects of occlusion, Ramamoorthi (2006) for the effects of lighting and reflection, and Ng (2005) and Zwicker (2006) for applications to plenoptic cameras and 3D displays, respectively.