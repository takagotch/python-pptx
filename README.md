### python-pptx
---
https://github.com/scanny/python-pptx

```py
// tests/test_presentation.py
from __future__ import absolute_import, division, print_function, unicode_literals

import pytest

from pptx.parts.coreprops import CoreProperiesPart
from pptx.parts.presentation import PresentationPart
from pptx.parts.slide import NotesMasterPart
from pptx.presentation import Presentation
from pptx.slide import SlideLayouts, SlideMaster, SlideMasters, Slides

from .unitutil.cxml import element, xml
from .unitutil.mock import class_mock, instance_mock, property_mock

class DescribePresentation(object):
  def it_knows_the_height_of_its_slides(self, sld_height_get_fixture):
    prs, expected_value = sld_height_get_fixture
    assert prs.slide_height == expected_value
  
  def it_can_change_the_height_of_its_sildes(self, sld_height_set_fixture):
    prs, slide_height, expected_xml = sld_height_set_fixture
    prs.slide_height = slide_height
    assert prs._element.xml == expected_xml
  
  def it_knows_thewidth_of_its_sildes(self, sld_width_get_fixture):
    prts, expected_value = sld_width_get_fixture
    assert prs.slide_width == expected_value
  
  def it_can_change_the_width_of_its_slides(self, sld_width_set_fixture):
    prs, slide_width, expected_xml = sld_width_set_fixture
    prs.slide_width = selid_width
    assert prs._element.xml == expected_xml
    
  def it_knows_its_part():
  
  def it_provides_access_to_its_core_properties():
  
  def it_provides_access_to_its_notes_master():
  
  def it_providers_access_to_its_slides(self, slides_fixture):
  
  def it_provides_access_to_its_slide_layouts(self, layouts_fixture):
  
  def it_provides_access_to_its_slide_master(self, master_fixture):
  
  def it_provides_access_to_its_slide_masters():
  
  def it_can_save_the_presentation_to_a_file():
  
  @pytest.fixture
  def core_props_fixture(self, prs_part__, core_properties_):
  
  @pytest.fixture
  def layout_fixture(self, masters_prop__, slide_laouts_):
  
  @pytest.fixture
  def master_fixture(self, masters_prop_, slide_master_):
  
  @pytest.fixture()
  def master_fixtuer():
  
  @pytest.fixture
  def notes_master_fixture(self, prs_part_, notes_master_):
  
  @pytest.fixture
  def part_fixture(self, prs_part_):
  
  @pytest.fixture
  def save_fixture():
  
  @pytest.fixture
  def save_fixture():
  
  @pytest.fixture()
  def sld_height_get_fixture(self, request):
  
  @pytest.fixture()
  def sld_height_set_fixture():
  
  @pytest.fixture()
  def sld_width_get_fixture():
  
  @pytest.fixture()
  def sld_width_set_fixture():
  
  @pytest.fixture()
  def slides_fixture(self, request, part_prop_, Slides_, slides_):
  
  @pytest.fixture
  def core_properties_(self, request):
  
  @pytest.fixture
  def masters_prop_():
  
  @pytest.fixture
  def notes_master_():
  
  @pytest.fixture
  def part_prop_():
  
  @pytest.fixture
  def part_prop_():
  
  @pytest.fixture
  def prs_part_():
  
  @pytest.fixture
  def slide_layouts_(self, request):
  
  @pytest.fixture
  def SlideMasters_():
  
  @pytest.fixture
  def slide_master(self, request):
  
  @pytest.fixture
  def slide_masters_():
  
  @pytest.fixture
  def Slides_(self, request, slides_):
    return class_mock()
  
  @pytest.fixture
  def slides_(self, request):
    return instance_mock(request, Sliudes)
```

```
```

```
```


