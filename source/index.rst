==============================================
 User Guide to Semiempirical Tight Binding
==============================================

This user guide focuses on the semiempirical quantum mechanical methods GFNn-xTB,
their descendants, and corresponding composite schemes as implemented in the
`xtb <https://github.com/grimme-lab/xtb>`_ (extended tight binding) program package.

We provide a number of detailed guides dealing with common tasks that can
be performed easily with the ``xtb`` program.
All guides are usually structured the same way, starting with some simple
examples using only the command line and the default settings, followed
by a troubleshooting section.
Detailed inputs are provided in a ready-to-use fashion to solve some
more special but still common tasks with ``xtb`` together with some
insights into the theory used behind the scenes.


-------------
 Quick Links
-------------

.. figure:: https://github.com/awvwgk/xtb-logo/raw/master/xtb.svg
   :width: 25%
   :alt: xtb
   :align: center

   `Documentation for xtb <setup.html>`_

.. figure:: https://github.com/grimme-lab/crest/raw/master/assets/crest.png
   :width: 25%
   :alt: CREST
   :align: center

   `Documentation for CREST <https://crest-lab.github.io/crest-docs/>`_

.. figure:: ../figures/CENSO/censo_logo_300dpi.png
   :width: 25%
   :alt: CENSO
   :align: center

   `Documentation for CENSO <CENSO_docs/censo.html>`_

.. figure:: ../figures/qcxms/qcxms_logo.svg
   :width: 25%
   :alt: QCxMS
   :align: center

   `Documentation for QCxMS <qcxms_doc/qcxms.html>`_


.. figure:: ../figures/qcxms2/qcxms2_logo.svg
   :width: 25%
   :alt: QCxMS2
   :align: center

   `Documentation for QCxMS2 <qcxms2_doc/qcxms2.html>`_   

.. figure:: ../logo/logo_abtgrimme_desktop.png
   :width: 25%
   :alt: Grimme-lab
   :align: center

   `Explore on GitHub <https://github.com/grimme-lab>`_

--------------------------------------------
 Recent developments, news, and publications
--------------------------------------------

.. postlist:: 5
   :date: %Y-%m-%d
   :format: {date}: {title} by {author}
   :excerpts:

See the :ref:`news archive <news>` for all posts.

-----------------------------------------
 xTB in Other Quantum Chemistry Programs
-----------------------------------------

The xTB-methods are now officially available in other quantum chemistry programs!

 - in `Orca`_ 4.2 an IO-based interface to the ``xtb`` binary is available
 - `AMS`_ 2019 implements GFN1-xTB in their DFTB module
 - the `entos`_ program implements GFN1-xTB (also available in the web interface)
 - the computational chemistry framework `cuby4`_ supports ``xtb``
 - `Turbomole`_ does support GFN1-xTB and GFN2-xTB since version 7.4
 - `QCEngine`_ supports calculations with the ``xtb`` API
 - the `GMIN`_, `OPTIM`_, and `PATHSAMPLE`_ global optimization tools provide an ``xtb`` interface
 - `CP2K`_ has a GFN1-xTB implementation since version 7.1
 - `DFTB+`_ support GFN1-xTB and GFN2-xTB since version 21.2

.. _Orca: https://orcaforum.kofo.mpg.de
.. _AMS: https://www.scm.com/product/dftb/
.. _entos: https://www.entos.info/
.. _cuby4: http://cuby4.molecular.cz/interface_xtb.html
.. _Turbomole: https://www.turbomole.org/
.. _QCEngine: http://docs.qcarchive.molssi.org/projects/QCEngine
.. _GMIN: http://www-wales.ch.cam.ac.uk/examples/GMIN
.. _OPTIM: http://www-wales.ch.cam.ac.uk/OPTIM
.. _PATHSAMPLE: http://www-wales.ch.cam.ac.uk/PATHSAMPLE/
.. _CP2K: https://www.cp2k.org/version_history
.. _DFTB+: https://www.dftbplus.org/

We missed your project here?
No problem, just give us a hint at the mailing list or open an issue at `GitHub`_.

.. _GitHub: https://github.com/grimme-lab/xtb_docs/issues/new


.. toctree::
   :maxdepth: 3
   :caption: Quickstart

   setup
   basics
   commandline
   geometry
   xcontrol
   development

.. toctree::
   :maxdepth: 3
   :caption: Guides

   sp
   properties
   optimization
   scan
   gbsa
   hessian
   md
   mtd
   oniom
   dipro
   path
   gsm
   periodic_boundary_conditions
   pcem
   gfnff
   ptb
   spgfn
   capi
   python
   community/index

.. toctree::
   :maxdepth: 3
   :caption: Submodules

   xtb_info
   xtb_docking
   xtb_thermo
   xtb_ir
   xtb_topo

.. toctree::
   :maxdepth: 3
   :caption: CREST

   crestxmpl

.. toctree::
   :maxdepth: 3
   :caption: ENSO
   
   enso_doc/enso
   enso_doc/enso_setup
   enso_doc/enso_usage
   enso_doc/enso_anmr
   enso_doc/plotting


.. toctree::
   :maxdepth: 3
   :caption: CENSO
   
   CENSO_docs/censo
   CENSO_docs/censorc
   CENSO_docs/censo_nmr
   CENSO_docs/abbreviations
   CENSO_docs/censo_extensive_keywords
   CENSO_docs/censo_parallel
   CENSO_docs/censo_implementation

.. toctree::
   :maxdepth: 3
   :caption: QCxMS
   
   qcxms_doc/qcxms
   qcxms_doc/qcxms_setup
   qcxms_doc/qcxms_run
   qcxms_doc/qcxms_plot
   qcxms_doc/qcxms_ex
   qcxms_doc/qcxms_cites

.. toctree::
   :maxdepth: 3
   :caption: QCxMS2
   
   qcxms2_doc/qcxms2
   qcxms2_doc/qcxms2_setup
   qcxms2_doc/qcxms2_run
   qcxms2_doc/qcxms2_plot
   qcxms2_doc/qcxms2_ex
   qcxms2_doc/qcxms2_cites


.. toctree::
   :maxdepth: 3
   :caption: Misc

   news
   versions
   xtbrelatedrefs
   license
   help

