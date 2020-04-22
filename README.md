### Novenyhatarozo, webes, cloud


### TODO / IN PROGRESS / DONE
---
INPROGRESS  
- decide on infrastructure

TODO  


DONE  
- done

---


#### Backend:

- data store / cloud functions: firebase, digital ocean ? (gcp, aws, azure)
- image processing: 
    - cloudinary (25 credits for storage/traffic allin), 
    - rokka (2gb storage/5g traffic)
- use brotli compression everywhere


#### Features:

* name (magyar es latin, esetleg angol)
  - names are searchable
* short description (max. 1500 chars) (esetleg + angolul)
* multiple images can be added 
  - stored in webp format packed, reduced file size, browsers can show
  - image has an overlay when shown, baked onto image? or not defined on upload
  - images marked for comparison -> maybe mark 2/3 entries for comparison, then show
    their pictures at top, and pick 2 to compare, allow zooming, etc. interesting!
* multiple tags added to an entry
  - entries are searchable
* maybe PWA app -- some data are saved locally too to ease burden on server
  - also server should store timestamps on everything to allow local cache invalidation
* authenticate login with facebook / google
  - allow comments to be sent for logged in user?
