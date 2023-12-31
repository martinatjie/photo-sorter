# 📸 **Photo Sorter** 🖼️
A photo organizing app that works with image recognition to sort photos into folders according to their graphical attributes.

## Examples
- Photos of dogs could be organized into a folder called 'dogs'.
- Christmas photos could be added to a Christmas folder.
- Photos of a specific couple could be added to a folder dedicated to them.

## The Big Idea
- As someone who stores (pretty much dumps!) a lot of photos on my hard drive, especially from my phone when it runs out of space, I need an app that can help me organize my photos in at least a semi-automated fashion (the more automated, the better).
- I don't just want to sort photos by date and location, because most file viewers etc. already do this.
- I want my app to move photos into folders according to certain rules.
- These rules should not be predetermined by the developer, but should rather be able to be set up by the user of the app, because every person has different things that are important to them and would therefore want different folder categorizations.
- I would like the app to tell me with how much certainty it thinks a photo belongs in a specific location.
- Furthermore, I want the app to allow the user to set a threshold which would allow auto-moving of photos into a folder if that threshold has been hit. E.g. if the user is okay with a confidence rating of 0.6, then any photo that meets a criteria with a confidence rating of 0.6 or more will be auto-moved without user intervention / vetting.
- Lastly, I'd want to give a user the option to set whether they want blurry photos to be auto-deleted, or even for the app to choose the best resolution photo of a bunch of photos of the same subject.

### _Why do I want photos to be organized into folders in the first place?_
Once I dump my photos, I very rarely look at them again because they are unorganized. The good photos sit in between gifs from Whatsapp and pixelised "good night" pictures from mom and friends. This also prevents me from printing physical albums of my photos because it would just be a huge endeavour to find fitting photographs.

### _But why folders, why not tags or something else?_
If there is a better alternative, I'm open for it. I'm happy to explore different organizing options.

## Future Development Ideas
If this app could be enhanced to create printable PDF's of albums, that would be awesome.
Here I'm thinking to give the user a couple of layout options.
The app can determine whether a photo is portrait or landscape, and what area on a photo is the most important so that if the image needs to get cropped, it will be done in such a fashion that e.g. a face isn't cut off by mistake.

## The Roadmap, MVP's & User Stories

Breaking down the development process for the "Photo Sorter" app involves several stages. Here's a suggested roadmap, an MVP (Minimum Viable Product), and potential user stories to guide the development process:

### Roadmap:
#### 1. Research and Planning:
- Study image recognition APIs and algorithms for identifying graphical attributes.
- Determine frameworks or technologies suitable for the app's development.
- Conduct user surveys or interviews to gather preferences for photo organization.
#### 2. MVP Development:
##### Basic Folder Sorting:
- Implement the ability to create folders and move photos manually.
##### Image Recognition:
- Integrate an image recognition API to identify basic attributes like dogs, Christmas, etc.
##### User Rules Setup:
- Design a user-friendly interface to allow users to set rules for photo categorization.
##### Confidence Rating and Threshold:
- Calculate confidence ratings for categorized photos and allow user-defined threshold settings.
##### Optional: Blurry Photo Handling:
- Implement an option for auto-deleting blurry photos.
#### 3. Enhancements and Additional Features:
##### Improved Image Recognition:
- Upgrade image recognition capabilities to identify more complex attributes or people's faces.
##### Alternative Organizing Options:
- Explore and implement other organizing methods like tags, metadata, or AI-based suggestions.
##### Album Creation and PDF Generation:
- Develop functionality to create printable PDF albums with various layout options.
##### Image Cropping Enhancement:
- Improve cropping algorithms to prevent important elements from getting cut off.

### User Stories:
- As a user, I want to create custom folders based on specific criteria.
- As a user, I want to define rules for automatic photo sorting into these folders.
- As a user, I want to set confidence thresholds for automatic sorting.
- As a user, I want the option to auto-delete blurry photos.
- As a user, I want the app to recognize different subjects like people, events, or pets.
- As a user, I want the ability to generate printable PDF albums with different layouts.

### MVP Features Breakdown:
- **Folder Creation and Manual Sorting:** Allow users to create folders and manually move photos into them.
- **Basic Image Recognition:** Implement image recognition to sort photos based on basic attributes (dogs, Christmas, etc.).
- **User Rules Setup:** Design a user interface for setting rules for photo categorization.
- **Confidence Rating and Threshold:** Calculate confidence ratings for categorized photos and allow users to set a threshold for automatic sorting.
- **Optional:** Blurry Photo Handling: Implement an option for auto-deleting blurry photos.

Breaking down development into these stages ensures a gradual and manageable progression while delivering essential functionality at each step. As the MVP gains traction, more advanced features and enhancements can be introduced based on user feedback and evolving needs.

