# The Big Idea 

We collect a lot of data from the USPTO. A _lot_ of data. Frequently, however, this data is not as well documented as we might desire. Further, it is often useful to see data in other contexts when examining a new problem. Therefore, we're going to try and create a Wiki in this repository outlining the sundry datasets at our disposal. Gideon has generated an [example page](https://github.com/liegroup-stanford/USPTO_Data_Guide/wiki/Orange-Book) on the Orange Book data to give an idea of what a page could look like. 

Note that eventually all materials from [this](https://github.com/liegroup-stanford/liegroup_notes/wiki/Patent-Data-Resources) page should be integrated, and that page should be deleted.

# What is a Wiki?

## Concept

A wiki is a communally-edited publication collecting information about a given topic. The most famous wiki is undoubtedly Wikipedia, though there exist scores of smaller, more specialized wikis as well. One example we quite like is the US Congress Wiki, which consolidates all information about legislation in congress. 

We think the USPTO data is a fitting subject for a wiki as many different people handle the same data, and therefore will need to reduplicate effort learning the data if knowledge is not stored somewhere. Moreover, the USPTO data is highly interconnected; entries in the applications data correspond to entries in the grants data, and those entries correspond to entries in the Orange Book data. Therefore, looking at a single dataset in a vacuum is insufficient; we also need to document the relationships between datasets. 

This brings us to the project at hand&ndash;documenting each USPTO dataset and its relationships to others in a single wiki. Given Heidi's many collaborators, grad students, and RAs, it makes sense to try and consolidate as much knowledge as possible in a single location, which is then accessible and editable by all. The hope is that each wiki page will contain all significant information on the relevant data set. Potential content includes an overview of the dataset, a list of publications using the data, the source where we retrieved the data, the process by which raw data is transformed into usable files, and a description of each .dta file generated.

## Style

The flexibility of wikis is both a blessing and a curse. It is simple to add and edit content as desired; however, it is difficult to standardize this content and ensure it is of consistent quality. For this reason, Wikipedia publishes its own Manual of Style, outlining what a Wikipedia article "should" look like. This is significant overkill for our project; however, when in doubt, the the Manual is a good place to check how to structure your wiki entries.

As a general rule, try and keep all information regarding a dataset on a single page divided into many subsections. While a wiki of small, highly connected pages sounds nice, it almost universally becomes cluttered with orphans and dead-ends. While not problematic in themselves, these pages can lead to duplicated&ndash;or worse, contradictory&ndash;information within a wiki, and make it difficult to know you've seen all information pertaining to a given dataset. Instead, GitHub wikis allow links to subsections of pages. Anytime you consider creating a new page, consider whether it would make more sense as a subsection of an existing page.

One place we pull away from the Wikipedia style is in terms of external links. Because Wikipedia tries to be all-encompassing, they require all links to refer to other Wikipedia pages. We don't have this problem&ndash;when referring to a professor or paper, please do include a link to their faculty or JSTOR page, respectively. Make sure to link to the source for any given dataset. In general, relevant external links are highly encouraged.

# Running the builds

As part of going over the USPTO datasets, we'd appreciate if you can rebuild them as well. Ideally, this should simply involve running a batch script in the folder and waiting for the results. However, between our migration to Stanford and some data reorganization, there's some concern that our builds may not be running at the moment. Given you'll be reading over the files anyway, we're hoping you'll also run the builds and ensure that, for example, all file paths are still accurate. By the end, the hope is that rebuilding again later _will_ be as simple as just running the batch script, even if it's not quite there yet.

# Starting Datasets

We have several datasets which need documenting. Below find a list of raw directories suitable for this wiki:
* USPTO_assignments
* USPTO_CPC
* USPTO_fees
* USPTO_PAIR
* USPTO_tech_centers
* USPTO_applications
* FDA_orphan_drugs
* FDA_purple_book
* GS_patent
* IMS_drug_patents
* PatentLens
* The forthcoming citations directories
