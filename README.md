# Building a Graph Native ML Pipeline for detecting Money Mules
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/neo4j-product-examples/demo-paysim-ml/blob/main/PaySim_Node_Classification_Demo.ipynb)

## The Dataset
The dataset uses a synthetic p2p money network called [PaySim][1].

While you can use the [PaySim Demo Loader][2] to bootstrap a new database, you
can take a shortcut and download the provided [dump file][3]. Follow the Neo4j
docs on [loading dump files][4] or [pushing them to Aura][5].

## The Bloom Perspective
To recreate the Bloom experience shown in the demo, download the provided
[perspective][6] file which you can [import][7] into Neo4j Bloom.

## The IPython Notebook
The heart of the demo lies in the provided [notebook][8]. In order to run it,
you'll need the following pre-requisites:

1. An IPython environment, like Jupyter, with a Python3 kernel.
2. Ability to `pip install` packages.
3. Connection details to a Neo4j AuraDS or Neo4j Enterprise server (with the
   GDS v2.1.x plugin installed).
   - Make sure to update the notebook with your connection details!

> The notebook _may_ work with Neo4j Community Edition, but it's untested.

[1]: https://www.sisu.io/posts/paysim/
[2]: https://github.com/voutilad/paysim-demo
[3]: ./neo4j.dump
[4]: https://neo4j.com/docs/operations-manual/current/backup-restore/restore-dump/
[5]: https://neo4j.com/docs/operations-manual/current/tools/neo4j-admin/push-to-cloud/
[6]: ./PaySim.json
[7]: https://neo4j.com/docs/bloom-user-guide/current/bloom-perspectives/perspective-creation/
[8]: ./PaySim_Node_Classification_Demo.ipynb
