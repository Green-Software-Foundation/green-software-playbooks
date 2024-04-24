# WebApp Guidelines

_Created by Edwin Cantu last modified on Jul 24, 2023_

## Purpose:

The goal of this rubric is to aide developers in what steps to take/implement to make sure the WebApp created is as green as possible.

## Low effort

    Semi optimized query
    Semi cache the taxing query
    Small modifications for resource allocation

These recommendations would include changes that would require minimal effort, such as reduced the allocation of resources where over-allocated.

## Medium effort

    Use partitioned tables
    Partial caching mechanism implemented within WebApp
    Partial modification for resource allocation
    Partially optimized Front End
    Implement resource monitors 

These would include suggestions on changes that would not be considered minimal.  For example, determining the optimal times to run a cronjob, or using a datacenter that is cleaner.

## High effort

    Query optimization 
    Memory utilization of 90% and above
    Cache frequently used calls within WebApp
    Select most appropriate language for WebApp use case
    Reserving only needed resources
    Full optimization of WebApp front end (IE Font optimization, Picture optimization, and JavaScript optimization/reduction)

Such suggestions would include changes that would require high effort on the part of product teams, such as using a language or framework that is significantly more efficient than the current one.
