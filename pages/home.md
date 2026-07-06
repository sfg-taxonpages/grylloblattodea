---
layout: blank
---
<GalleryCarousel :depiction-id="[]" height="470px">
  <div class="flex flex-col justify-center items-center w-full h-full bg-black/25 text-white gap-4 px-4 box-border">
    <span class="text-4xl font-medium">{{ app:project_name }}</span>
    <p class="text-lg sm:text-xl">A comprehensive source of knowledge on the world’s cockroaches and termites</p>
    <div class="mx-auto flex flex-col items-center mt-6 sm:mt-10 w-full">
      <autocomplete-otu class="w-full sm:w-96 text-base-content ml-2 sm:ml-0" placeholder="Search by taxon name" autofocus/>
        <p class="text-sm sm:text-base"><em>Explore! Try searching for any taxa from order <router-link to="/otus/856752">Blattodea</router-link> or just type Blattella to get started</em></p>
    </div>
  </div>
</GalleryCarousel>
        
<div class="container mx-auto my-8 px-4 md:px-0 box-border">


# {{ app:project_name }}
The Grylloblattodea Species File works to build a comprehensive source for knowledge about the world’s ice crawlers. Information found here includes valid names, synonyms, bibliographic data, specimen data, images, and distributions for ice crawlers of the world. Our site seeks to include and serve researchers in taxonomy, systematics, ecology, ethology, conservation, and evolution, as well as educators, policy makers, and citizen scientists.

## Search

<autocomplete-otu class="w-full sm:w-96" placeholder="Search by taxon name"/>

Explore!

Try searching for species _Grylloblatta berberi_, or start your exploration at Genus [Grylloblatta](/otus/925108/overview),  or Family [Grylloblattidae](/otus/925080/overview).

## Discover more
See our [About](about) page for an [overview](about#overview) of the project, its data, the development [team](about#project-development-and-maintenance), and details about how you can [access the data, contribute, contact us, or get help](about#contribute-or-get-help). 

## Announcements

### Sept. 15, 2023: Welcome to our new Grylloblattodea Species File Website
<p>We look forward to hearing from you about your experiences with our new features as well as how you use the information you find here.</p>
