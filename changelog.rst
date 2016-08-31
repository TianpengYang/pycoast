Changelog
=========

%%version%% (unreleased)
------------------------

- Update changelog. [Martin Raspaud]

- Bump version: 0.5.4 → 0.5.5. [Martin Raspaud]

- Update fonts in two test images. [Martin Raspaud]

- Update changelog. [Martin Raspaud]

- Bump version: 0.5.3 → 0.5.4. [Martin Raspaud]

- Merge branch 'pre-master' [Martin Raspaud]

- Merge branch 'pre-master' of github.com:pytroll/pycoast into pre-
  master. [Martin Raspaud]

- Add missing import of ConfigParser. [Panu Lahtinen]

- Remove skipping shapefiles crossing dateline, fixes global overlays.
  [Panu Lahtinen]

- Update test reference images with ones made in Ubuntu so automatic
  testing might work in Travis. [Panu Lahtinen]

- Update changelog. [Martin Raspaud]

- Bump version: 0.5.2 → 0.5.3. [Martin Raspaud]

- Merge branch 'master' into pre-master. [Martin Raspaud]

  Conflicts:
  	.gitignore
  	setup.py

- Add a gitignore file. [Martin Raspaud]

- Merge pull request #2 from mitkin/master. [Martin Raspaud]

  Update setup.py

- Update setup.py. [Mikhail Itkin]

- Fix pyproj missing dependency. [Martin Raspaud]

- Move the test directory to pycoast.tests (for consistency) [Martin
  Raspaud]

- Fix .travis.yml to install aggdraw first. [Martin Raspaud]

- Merge branch 'restructure' into pre-master. [Martin Raspaud]

- Split different readers out of __init__.py, adjust __init__.py so that
  everything still works in the same way as previously. [Panu Lahtinen]

- More generic ignores. [Panu Lahtinen]

- Add a test suite and .travis file for ci. [Martin Raspaud]

- Update the reference images to make the test pass with pillow/aggdraw.
  [Martin Raspaud]

- Add numpy to the list of dependencies. [Martin Raspaud]

- Added documentation about configuration files for pycoast. [Martin
  Raspaud]

- Add setup.cfg for easy rpm generation. [Martin Raspaud]

- Bugfix: The section is called "coasts", plural... [Martin Raspaud]

- Bugfix: the refactoring used only coastal style. [Martin Raspaud]

- Some refactoring and pep8. [Martin Raspaud]

- _add_shapefile_shape bug fixed. [s.cerino]

- Merge branch 'master' into pre-master. [Martin Raspaud]

- Add configuration file reading feature. [Martin Raspaud]

- Merge branch 'master' of https://code.google.com/p/pycoast. [Martin
  Raspaud]

- Fixed (sometimes fatal) ImageDraw import. [Hrobjartur Thorsteinsson]

  ImageDraw and other PIL modules should be imported
  directly from prevailing PIL package.


- Merge branch 'master' of https://code.google.com/p/pycoast. [Martin
  Raspaud]

- Merge branch 'master' of https://code.google.com/p/pycoast. [Martin
  Raspaud]

- Merge branch 'master' of https://code.google.com/p/pycoast. [Martin
  Raspaud]

  Conflicts:
  	pycoast/__init__.py


- Removing the rounding of the pixel indices. (Works with AGG and
  without). [Martin Raspaud]

- Docbuilds. [Hrobjartur Thorsteinsson]

  docbuilds


- Added documentation for polygons and shapefile methods. [Hrobjartur
  Thorsteinsson]

  Added documentation for polygons and shapefile methods.


- Add_polygon and add_shapefile_shape(s) integration testing.
  [Hrobjartur Thorsteinsson]

  add_polygon and add_shapefile_shape(s) integration testing.
  Also included preliminary test data.


- Work in progress setting up shape and cities support. [Hrobjartur
  Thorsteinsson]

  Work in progress setting up shape and cities support


- Removed print line from add_shape routine. [Hrobjartur Thorsteinsson]

  removed print line from add_shape routine


- Make pillow a dependency if PIL is not already there. [Martin Raspaud]

- Fixed fata ImageDraw import. [Hrobjartur Thorsteinsson]

  Fixed importing conflict, affecting some users
  seemingly with mixed installations of PIL/Pillow.

  all PIL imports should be from same package.
  made "from PIL import ImageDraw"


- Adding appertizer image at the front. [Adam Dybbroe]

- Rearranging documentation, and minor editorial stuff. [Adam Dybbroe]

- Bug fix: add_line / add_polygon. [Hrobjartur Thorsteinsson]

  Minor bug fix: add_line / add_polygon exception.


- Added custom shapefile and shape draw routines. [Hrobjartur
  Thorsteinsson]

  custom shapefile and shape draw routines.

  add_shapefile_shape(...)
  add_shapefile_shapes(...)
  add_line(...)
  add_polygon(...)


- Built docs. [Esben S. Nielsen]

- Hrobs changes and FFT metric for unit test. [Esben S. Nielsen]

- Flexible grid labeling and placement implemented. [Esben S. Nielsen]

- Lon markings now account for dateline too. [Esben S. Nielsen]

- Updated doc image. [Esben S. Nielsen]

- Updated docs. [Esben S. Nielsen]

- Test updated. [Esben S. Nielsen]

- Implemented correct dateline handling and updated tests. [Esben S.
  Nielsen]

- Added all of docs/build/html. [Esben S. Nielsen]

- Modified comment. [Esben S. Nielsen]

- Added graticule computation from Hrob. [Esben S. Nielsen]

- Corrected bug in add_coastlines_to_file. [Esben S. Nielsen]

- Bugfixing to improve accuracy. [Esben S. Nielsen]

- Added testing. [Esben S. Nielsen]

- Corrected docs. [Esben S. Nielsen]

- Corrected git doc mess. [Esben S. Nielsen]

- Updated docs. [Esben S. Nielsen]

- Added possiblility to use AGG. Changed API slightly. [Esben S.
  Nielsen]

- Docs messed up by git. Trying to clean. [Esben S. Nielsen]

- Added missing build doc files. [Esben S. Nielsen]

- Corrected invalid reprojection issue for projections like geos. [Esben
  S. Nielsen]

- Rebuild docs. [Esben S. Nielsen]

- Bumped up version. [Esben S. Nielsen]

- Corrected south pole filtering bug. [Esben S. Nielsen]

- Changed link to SOEST. [Esben S. Nielsen]

- Documented project. [Esben S. Nielsen]

- Added license and docs. [Esben S. Nielsen]

- Now handles poles. [Esben S. Nielsen]

- Added docstrings. [Esben S. Nielsen]

- Added test. [Esben S. Nielsen]

- Created package. [Esben S. Nielsen]

- Restructured pixel index calculation. [Esben S. Nielsen]

- Added borders and rivers. [Esben S. Nielsen]

- First version. [Esben S. Nielsen]

- First version. [Esben S. Nielsen]


