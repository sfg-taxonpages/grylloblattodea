---
# See project.yml for variables.
---
# About
Gathering knowledge about the following extant insect groups: Archaeognatha (Microcoryphia), Coleorrhyncha, Embioptera, Notoptera (Grylloblattodea and Mantophasmatodea), Zoraptera and Zypentoma (Thysanura); and the following extinct groups: Archaeorthoptera, Cnemidolestida, Eoblattida, Permopsocida and Reculida

## Overview
The _{{ app:project_name }}_ file offers a collection of richly-cited and annotated information on a number of small insect orders, extant and fossil. Data found here come from a collaboratively compiled database originating in an instance of [TaxonWorks](https://taxonworks.org) managed by the [Species File Group](https://speciesfilegroup.org). See [Contribute or get help](#contribute-or-get-help) for how you can participate. This site is built using TaxonPages, [learn more here](https://github.com/SpeciesFileGroup/taxonpages). For more on how this site is built please see the [Software](#software) section.

## Project development and maintenance

|name|role|
|----|----|
| Heidi Hopkins | Lead Curator |
| Tom Klein | Contributor |
| Michael D. Maehr\* | Author |
| David C. Eades\* | Developer |

_\* Past contributor, now inactive._

### Contribute or get help
The Earth's biodiversity is vast and the data captured to describe it are minimal in comparison, but still immense. All projects of this nature contain gaps, i.e. opportunities for collaboration on future work, grants, and research. Known gaps in this project may include an incomplete catalog of type-material, incomplete photographic depictions, missing biological associations, incomplete distribution records, and more. Contact us to <TrackerReport label="Report a problem or offer data" tag="a" button-class="cursor-pointer" /> (bugs or data issues) on our issue tracker if you would like to help us address these or other gaps in the data, or if you find a bug.

- **Cite** this website: Hopkins, H., Selected Insecta Species File. [retrieval date]. <https://grylloblattodea.speciesfile.org>. See also [Terms of use](#terms-of-use).

### Extended data access
A goal of these pages is to ensure that the underlying data behind them are accessible in their digital format. By diversifying the ways the data are accessible (e.g. on the web page, in JSON, in Darwin Core standard), we increase the opportunities to both spot errors and provide new services and portals.

- Researchers working on this project use their rich, multi-faceted access to the data via TaxonWorks' interfaces (e.g. filters, reporting, downloads). Access requires a project account, see **Contribute or get help**.
- Data behind individual panels per page can be seen via the _Sitemap_ functionality.
- Each page offers an option to download a _DarwinCore formatted table_ containing all data for this taxon and its children.
- Panel data (each section on a page) and other information not available on these pages are accessible via a [TaxonWorks API](https://api.taxonworks.org) at [https://sfg.taxonworks.org/api/v1](https://sfg.taxonworks.org/api/v1).
- Core taxonomic data are exported to and available at the [Catalogue of Life](https://www.catalogueoflife.org/data/dataset/1170).

### Software
These pages are built with open-source software. [Read more here](http://speciesfilegroup.org/docs/taxonworks_in_production_at_sfg.html) about what drives them and how they are supported by the Species File Group and their many collaborators. To get further involved [join weekly support meetings here](https://speciesfilegroup.org/events.html).

## History
In August 2023 all data in the former Species File Websites were frozen and shortly thereafter migrated to TaxonWorks. As with all migrations of this nature the process is both lossy (e.g. some data could not be mapped with certainty) and improved (e.g. semantics of the new models have more precision and clarity). If you spot something that needs attention, please see **Contribute or get help**.

In July 2026 six species file databases were combined to form Selected Insecta Species File, and six new groups of extant and extinct insects were added that did not previously have SFG coverage.

## Support and funding
This database functionality and content is serviced in part by the Species File Group.

## Terms of use

<div class="flex items-center gap-2">
  <a
    class="min-w-fit"
    href="{{ app:copyright_image_link }}"
  >
    <img 
      src="{{ app:copyright_image }}" 
      alt="copyright" 
      class="m-0"
    >
  </a>
  <span>{{ app:copyright_text }}</span>
</div>

