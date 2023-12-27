# NotionWise

### Notion <-> Readwise bi-directional sync

Provides [ListerWatcher](https://javadoc.io/doc/io.fabric8/kubernetes-client/4.6.1/io/fabric8/kubernetes/client/informers/ListerWatcher.html)-like functions on
- Readwise Reader inbox
- A set of Notion pages

that can be combined with ```Publish``` jobs to:
- Create new Notion Pages or Database entries
- Export highlights to Readwise

For eg:
- Watches for new entries in Readwise Reader inbox and creates new Notion pages for each article in the desired location
- Watches a list of pages for updates and creates Readwise highlights
 
  
