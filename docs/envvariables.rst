Imageio environment variables
=============================

This page lists the environment variables that imageio uses. You can
set these to control some of imageio's behavior. Each operating system
has its own way for setting environment variables, but to set a variable
for the current Python process use
``os.environ['IMAGEIO_VAR_NAME'] = 'value'``.

* ``IMAGEIO_NO_INTERNET``: If this value is "1", "yes", or "true" (case
  insensitive), makes imageio not use the internet connection to
  retrieve files (like libraries or sample data). Some plugins (e.g.
  freeimage and ffmpeg) will try to use the system version in this case.
* ``IMAGEIO_FFMPEG_EXE``: Set the path to the ffmpeg executable. Set
  to simply "ffmpeg" to use your system ffmpeg executable. If not given,
  will try to download the ffmpeg exe that imageio provides.
* ``IMAGEIO_AVBIN_LIB``: Set the path to the avbin library. If not
  given, will try to download the avbin library that imageio provides.
* ``IMAGEIO_FREEIMAGE_LIB``: Set the path to the freeimage library. If
  not given, will try to download the freeimage library that imageio
  provides.
