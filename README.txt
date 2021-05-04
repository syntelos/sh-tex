
Overview

  Toolsets to subsume common writing operations to simple commands.

  Series

    The 'series' tool works from a directory 'prefix/prefix-series'
    (e.g. 'tex/tex-journal') to produce a TeX journal.  It manages the
    TeX files in a journal so that writing is a fluid process
    unhindered by technicalities.

    Journal directory 'prefix/prefix-series' is expected to be a git
    repository with annual "circa" subdirectories, e.g. 2020 or 2021.

    The file <create> process expects
    '<prefix>/<prefix-series>/<circa>/template.tex' (alt env
    TEX_SERIES_TEMPLATE) which is copied into place on creation.  The
    file <create> process will employ emacs (alt env
    TEX_SERIES_EDITOR) to edit the initial file product of creation.

  Archive

    The 'archive' tool is an independent conglomeration of the toolbox
    concept into a related artefact.  In this case, the toolbox
    produces /home/usr/Pictures/archive from Screenshot files in
    /home/usr/Pictures, and encodes daily MPEG-4 summations from an
    index.  It also maintains a labels list.

    The 'archive' tool enables workspace recording and sharing.  This
    is useful for work effort visualization, work technique
    illustration, work flow presentation, and other information -
    experiential recording from the workstation.

See also

  https://github.com/syntelos/tex-journal

