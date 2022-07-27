# Multilanguage Bazel Monorepo

## Setup

1. `npm i -g @bazel/bazelisk`
1. Clone the repo

## Description

Currently the repo has Go and Node.js set up.

|Name|Version|
| --- | --- |
|Go|`1.18.4`|
|Bazel|`5.2.0`|
|Bazelisk|`1.12.0`|
|Gazelle|`0.26.0`|
|rules_go|`0.34.0`|

Folder structure should look like this:

```
|_ [Language Names]
	 |_ services
		  |_ [Runable Server Side Projects]
	 |_ apps
		  |_ [Runable Client Side Projects]
	 |_ libs
		  |_ [Libraries]
```