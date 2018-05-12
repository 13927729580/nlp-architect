.. ---------------------------------------------------------------------------
.. Copyright 2017-2018 Intel Corporation
..
.. Licensed under the Apache License, Version 2.0 (the "License");
.. you may not use this file except in compliance with the License.
.. You may obtain a copy of the License at
..
..      http://www.apache.org/licenses/LICENSE-2.0
..
.. Unless required by applicable law or agreed to in writing, software
.. distributed under the License is distributed on an "AS IS" BASIS,
.. WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
.. See the License for the specific language governing permissions and
.. limitations under the License.
.. ---------------------------------------------------------------------------

NLP Architect by Intel® AI Lab
######################

| **Release:**  |version|
| **Date:**     |today|

"""""""""""""""""""""""

NLP Architect is an open-source Python library for exploring the state-of-the-art deep learning topologies and techniques for natural language processing and natural
language understanding. It is intended to be a space to promote research and
collaboration.

The library includes our past and ongoing NLP research and development efforts as part of Intel AI Lab.

- Brief library :doc:`overview <overview>`
- :doc:`Installation <installation>` instructions


.. toctree::
   :hidden:
   :maxdepth: 1
   :caption: NLP Architect

   overview.rst
   installation.rst
   service.rst

.. toctree::
   :hidden:
   :maxdepth: 1
   :caption: NLP/NLU Components

   np2vec.rst
   chunker.rst
   ner_crf.rst
   ne_expansion.rst
   intent.rst
   np_segmentation.rst
   bist_parser.rst
   spacy_bist.rst
   word_sense.rst

.. toctree::
   :hidden:
   :maxdepth: 1
   :caption: End to End Models

   reading_comprehension.rst
   memn2n.rst
   kvmemn2n.rst


.. toctree::
  :hidden:
  :maxdepth: 1
  :caption: For Developers

  developer_guide.rst
  writing_tests.rst

.. toctree::
   :hidden:
   :maxdepth: 1
   :caption: Full API

   api.rst
