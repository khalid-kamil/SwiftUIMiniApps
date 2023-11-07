# SwiftUIMiniApps
16 mini-projects exploring  different frameworks and technologies in SwiftUI. Including UIKit integration, animations, CoreImage, CoreLocation, MapKit, CoreData, CoreHaptics and Accessibility. Inspired by and expanded upon Hacking With Swift's "100 Days of SwiftUI".

#### Split the bill
A check-sharing app that calculates how to split a check based on the number of people and how much tip you want to leave.
- Form
- Navigation bar
- Program State

[![Split the bill repo](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/khalid-kamil/SplitTheBill)

#### Better Rest - Sleep Calculator
An app designed to help coffee drinkers get a good night’s sleep by asking them three questions:
  1. When do they want to wake up?
  2. Roughly how many hours of sleep do they want?
  3. How many cups of coffee do they drink per day?
- Create ML and Core ML (training a model)

[![Better Rest repo](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/khalid-kamil/Project5-BetterRest)

#### Word Scramble Game
A game that shows players a random eight-letter word, and asks them to make words out of it. For example, if the starter word is “alarming” they might spell “alarm”, “ring”, “main”, and so on.
- List (adding to a list of words)
- Loading resources from app bundle (running code when your app launches)
- Working with strings (validating words with UITextChecker)

[![Word Scramble repo](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/khalid-kamil/WordScramble-SwiftUI)

#### Animations Explorations
- Creating implicit animations
- Customizing animations in SwiftUI
- Animating bindings
- Creating explicit animations
- Controlling the animation stack
- Animating gestures
- Showing and hiding views with transitions
- Building custom transitions using ViewModifier

[![Animations repo](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/khalid-kamil/SwiftUIAnimations)

#### Expense Calculator
An expense tracker that separates personal costs from business costs.
- Showing and hiding views - sharing an observed object with a new view
- Deleting items using onDelete() - building a list we can delete from
- Storing user settings with UserDefaults - making changes permanent with UserDefaults
- Archiving Swift objects with Codable
- Building a list we can delete from

[![iExpense repo](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/khalid-kamil/iExpense)

#### Moonshot - NASA Mission Info
An app that lets users learn about the missions and astronauts that formed NASA’s Apollo space program.
- Resizing images to fit the screen using GeometryReader
- Using ScrollView with scrolling data
- Pushing new views onto stack with NavigationLink
- Working with hierarchical Codable data - loading specific coddle data
- Using generics to load any kind of Codable data
- Scrolling grid views
- Formatting mission view

[![Moonshot repo](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/khalid-kamil/Moonshot)

#### Drawing shapes in SwiftUI
- Creating custom paths with SwiftUI
- Paths vs shapes in SwiftUI
- Adding strokeBorder() support with InsettableShape
- Transforming shapes using CGAffineTransform and even-odd fills
- Creative borders and fills using ImagePaint
- Enabling high-performance Metal rendering with drawingGroup()
- Special effects in SwiftUI: blurs, blending, and more
- Animating simple shapes with animatableData
- Animating complex shapes with AnimatablePair
- Creating a spirograph with SwiftUI

[![Drawing repo](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/khalid-kamil/Drawing-SwiftUI)

#### Cupcake Ordering App
A multi-screen app for ordering cupcakes
- Codable conformance for @Published properties
- Sending and receiving Codable data with URLSession
- Loading an image from a remote server
- Validating and disabling forms
- Taking basic order details
- Checking for a valid address
- Preparing for checkout
- Encoding an ObservableObject class
- Sending and receiving orders over the internet

[![Cupcake Corner repo](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/khalid-kamil/CupcakeCorner)

#### Bookworm - Book Review App
An app to track which books you’ve read and what you thought of them.
- Multi-line text input with TextEditor
- Combine Core Data and SwiftUI
- Creating books with Core Data
- Custom star rating component
- Building a list with @FetchRequest
- Show book details
- Sort fetch requests with SortDescriptor
- Delete from a Core Data fetch request
- Using an alert to pop a NavigationLink programmatically

[![Bookworm repo](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/khalid-kamil/Bookworm)

#### CoreData Explorations
- NSManagedObbject subclass
- Conditional saving of NSManagedObjectContext
- Ensuring Core Data objects are unique using constraints
- Filtering @FetchRequest using NSPredicate
- Dynamically filtering @FetchRequest with SwiftUI
- One-to-many relationships with Core Data, SwiftUI, and @FetchRequest

[![Core Data repo](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/khalid-kamil/CoreDataProject)

#### Instafilter - Simple Photo Editing App
An app that lets the user import photos from their library, then modify them using various image effects.
- How property wrappers become structs
- Responding to state changes using onChange()
- Showing multiple options with confirmationDialog()
- Integrate Core Image with SwiftUI
- Wrapping a UIViewController in a SwiftUI view
- Using coordinators to manage SwiftUI view controllers
- Saving images to the user’s photo library
- Importing an image into SwiftUI using PHPickerViewController
- Basic image filtering using Core Image
- Customizing our filter using confirmationDialog()
- Saving the filtered image using UIImageWriteToSavedPhotosAlbum()

[![Instafilter repo](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/khalid-kamil/Instafilter-SwiftUI)

#### Bucketlist - Mark cities to visit on the map
An app that lets the user build a private list of places on the map that they intend to visit one day, add a description for that place, look up interesting places that are nearby, and save it all to the iOS storage for later.
- Adding conformance ot Comparable for custom types
- Write data to the documents directory
- Switch view states with enums
- Integrate MapKit with SwiftUI
- Using Touch ID and Face ID with SwiftUI
- Add user locations to a map
- Improving our map annotations
- Selecting and editing map annotations
- Downloading data from wikipedia
- Sorting wikipedia results
- Introducing MVVM into your SwiftUI project
- Locking our UI behind Face ID

[![Bucketlist repo](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/khalid-kamil/BucketList)

#### Accessibility Explorations
- dentifying views with useful labels
- Hiding and grouping accessibility data
- Reading the value of controls

[![Accessibility repo](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/khalid-kamil/Accessiblity)

#### Prospects - Networking App
An app to track who you meet at conferences. It will show a QR code that stores your attendee information, then others can scan that code to add you to their list of possible leads for later follow up.
- Reading custom values from the environment with @EnvironmentObject
- Creating tabs with TabView and tabItem()
- Manually publishing ObservableObject changes
- Understanding Swift’s Result type
- Controlling image interpolation in SwiftUI
- Creating context menus
- Adding custom row swipe actions to a List
- Scheduling local notifications
- Adding Swift package dependencies in Xcode
- Building a tab bar
- Sharing data across tabs using @EnvironmentObject
- Dynamically filtering a SwiftUI List
- Generating and scaling up a QR code
- Scanning QR codes with SwiftUI
- Adding options with swipe actions
- Saving and loading data with UserDefaults
- Adding a context menu to an image
- Posting notifications to the lock screen

[![Prospects repo](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/khalid-kamil/Prospects)

#### Flash Card App
An app that helps users learn things using flashcards – cards with one thing written on such as “to buy”, and another thing written on the other side, such as “comprar”.
- How to use gestures in SwiftUI
- Making vibrations with UINotificationFeedbackGenerator and Core Haptics
- Disabling user interactivity with allowsHitTesting()
- Triggering events repeatedly using a timer
- How to be notified when your SwiftUI app moves to the background
- Supporting specific accessibility needs with SwiftUI
- Designing a single card view
- Building a stack of cards
- Moving views with DragGesture and offset()
- Coloring views as we swipe
- Counting down with a Timer
- Ending the app with allowsHitTesting()
- Making iPhones vibrate with UINotificationFeedbackGenerator
- Adding and deleting cards

[![Flashzilla repo](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/khalid-kamil/Flashzilla)

#### Layout and Geometry Explorations
- Alignments and alignment guides
- How to create a custom alignment guide
- Absolute positioning for SwiftUI views
- Understanding frames and coordinates inside GeometryReader
- ScrollView effects using GeometryReader

[![Layout repo](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/khalid-kamil/LayoutAndGeometry)

#### SnowSeeker - Ski Resort Browser
An app to let users browse ski resorts around the world, to help them find one suitable for their next holiday.
- Working with two side by side views in SwiftUI
- Using alert() and sheet() with optionals
- Using groups as transparent layout containers
- Making SwiftUI view searchable
- Building a primary list of items
- Making NavigationView work in landscape
- Creating a secondary view for NavigationView
- Searching for data in a List
- Changing a view’s layout in response to size classes
- Binding an alert to an optional string
- Letting the user mark favorites

[![SnowSeeker repo](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/khalid-kamil/SnowSeeker)
