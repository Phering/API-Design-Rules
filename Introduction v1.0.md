# Introduction

## Goal

More and more governmental organizations offer REST APIs (henceforth abbreviated as APIs), in addition to existing interfaces like SOAP and WFS. These APIs aim to be developer-friendly and easy to implement. While this is a commendable aim, it does not shield a developer from a steep learning curve getting to know every new API, in particular when every individual API is designed using different patterns and conventions.

This document aims to describe a widely applicable set of design rules for the unambiguous provisioning of REST APIs. The primary goal is to offer guidance for organizations designing new APIs, with the purpose of increasing developer experience (DX) and interoperability between APIs. Hopefully, many organizations will adopt these design rules in their corporate API strategies and provide feedback about exceptions and additions to subsequently improve these design rules.

## Status

This version of the design rules has been submitted to Forum Standaardisatie for inclusion on the Comply or Explain list of mandatory standards in the Dutch Public Sector. This document originates from the document [API Strategie voor de Nederlandse Overheid](https://docs.geostandaarden.nl/api/vv-hr-API-Strategie-20190715/), which was recently split into separate sub-documents.

## Authors

Despite the fact that two authors are mentioned in the list of authors, this document is the result of a collaborative effort by the members of the *API Design Rules Working Group*.

## Reading Guide

This document is part of the *Nederlandse API Strategie*.

| Part    | Description                                   | Status          | Link                                                        |
|---------|-----------------------------------------------| ----------------|-------------------------------------------------------------|
| I       | General description of the API Strategy       | Informative     | https://docs.geostandaarden.nl/api/API-Strategie/           |
| **IIa** | **Standard for designing APIs**               | **Normative**   | https://docs.geostandaarden.nl/api/API-Designrules/         |
| IIb     | Extension on the Standard for designing APIs  | Informative     | https://docs.geostandaarden.nl/api/API-Strategie-ext/       |