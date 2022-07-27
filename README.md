# Building a Graph Native ML Pipeline for detecting Money Mules

## The Dataset
The dataset uses a synthetic p2p money network called [PaySim][0].

While you can use the [PaySim Demo Loader][1] to bootstrap a new database, you
can take a shortcut and download the provided [dump file][2]. Follow the Neo4j
docs on [loading dump files][3] or [pushing them to Aura][4].

## The Bloom Perspective
To recreate the Bloom experience shown in the demo, download the provided
[perspective][5] file which you can [import][6] into Neo4j Bloom.

## The IPython Notebook
The heart of the demo lies in the provided [notebook][7]. In order to run it,
you'll need the following pre-requisites:

1. An IPython environment, like Jupyter, with a Python3 kernel.
2. Ability to `pip install` packages.
3. Connection details to a Neo4j AuraDS or Neo4j Enterprise server (with the
   GDS v2.1.x plugin installed).

> The notebook _may_ work with Neo4j Community Edition, but it's untested.

[0]: https://www.sisu.io/posts/paysim/
[1]: https://github.com/voutilad/paysim-demo
[2]: about:
[3]: https://neo4j.com/docs/operations-manual/current/backup-restore/restore-dump/
[4]: https://neo4j.com/docs/operations-manual/current/tools/neo4j-admin/push-to-cloud/
[5]: about:
[6]: https://neo4j.com/docs/bloom-user-guide/current/bloom-perspectives/perspective-creation/
[7]: about:
