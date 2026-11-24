# Portfolio Project Data — Aorus Gaming Showcase

- **Category:** `web-development` (`Web Development`)
- **Accent Color:** `cyan`
- **Target Assets Folder:** `public/images/projects/aorus_gaming_showcase/`
- **Required Local Images:** `banner.webp`, `image01.webp` .. `image08.webp`

## TypeScript Data (`ProjectCaseStudy`)

```typescript
{
  "id": "aorus-gaming-showcase",
  "code": "PRO-04 // WEB-01",
  "title": "Aorus Gaming Showcase",
  "category": "web-development",
  "categoryLabel": "Website",
  "year": "2021",
  "status": "Completed",
  "accentColor": "cyan",
  "repoUrl": "https://github.com/weztcy/Aorus-Gaming-Showcase",
  "license": "MIT License",
  "banner": "/images/projects/aorus_gaming_showcase/banner.webp",
  "summary": "Multi-page AORUS gaming hardware showcase featuring 22 product spec pages, editorial articles, interactive JS widgets, and PHP product registration.",
  "projectDescription": "Aorus Gaming Showcase is a responsive multi-page hardware catalog and editorial portal built with HTML5, CSS3, Vanilla JavaScript, and PHP. It organizes 22 detailed GIGABYTE AORUS products across four categories alongside benchmark articles, slideshows, and registration forms.",
  "architectureSummary": "Multi-page static HTML5/CSS3 frontend organized by domain folders, enhanced with modular Vanilla JavaScript widgets and a PHP POST form handler.",
  "techStack": [
    "HTML5",
    "CSS3",
    "JavaScript",
    "PHP",
    "HTML5 Video",
    "Responsive Web Design"
  ],
  "telemetryMatrix": {
    "projectType": "Multi-Page Hardware Showcase",
    "targetPlatform": "Desktop & Mobile Web Browsers",
    "primaryDomain": "Gaming Hardware & Tech Editorial",
    "architecturePipeline": "Static HTML5 / CSS3 / JS + PHP Form",
    "testingAndAudit": "Manual Cross-Viewport Verification",
    "projectStatus": "Completed",
    "projectYear": "2021"
  },
  "projectInfo": {
    "projectType": "Multi-Page Frontend Web Showcase",
    "developmentStatus": "Completed",
    "developmentYear": "2021",
    "platform": "Web Browser",
    "projectCategory": "Web Development"
  },
  "projectBackground": "Enthusiast PC builders and gamers need structured access to high-end hardware specifications, thermal engineering details, and real-world benchmarks in one unified interface. Aorus Gaming Showcase was engineered as a cohesive brand portal uniting product discovery, media, and editorial content.",
  "problemStatements": [
    {
      "title": "Fragmented Hardware Specification Discovery",
      "description": "High-performance PC components span distinct product lines—motherboards, GPUs, cooling, memory, storage, and laptops—making cross-category browsing tedious without a unified catalog hierarchy.",
      "issueCode": "ISSUE_01"
    },
    {
      "title": "Static Text-Heavy Product Pages",
      "description": "Plain specification sheets fail to communicate industrial design, RGB accents, and thermal subsystems such as WATERFORCE loops or Fins-Array heatsinks effectively.",
      "issueCode": "ISSUE_02"
    },
    {
      "title": "Disconnected Editorial & Brand Context",
      "description": "Shoppers comparing Z690 motherboards or RTX 30 series cards benefit from direct access to benchmark comparisons, technology explainers, and product registration within the same portal.",
      "issueCode": "ISSUE_03"
    }
  ],
  "projectObjectives": [
    {
      "title": "Unified Four-Category Hardware Catalog",
      "description": "Structure 22 dedicated product detail pages under Motherboards, Graphics Cards, PC Components, and Gaming Laptops with consistent navigation and sticky category jump links.",
      "targetTag": "TARGET_01"
    },
    {
      "title": "Interactive Multimedia & Responsive Presentation",
      "description": "Combine looping background MP4 videos, embedded YouTube reviews, interactive JavaScript image slideshows, and CSS3 media queries across desktop, tablet, and mobile screens.",
      "targetTag": "TARGET_02"
    },
    {
      "title": "Integrated Editorial & Registration Flows",
      "description": "Deliver seven formatted technical articles under Explore #AORUS alongside a PHP POST product registration workflow for serial number and purchase capture.",
      "targetTag": "TARGET_03"
    }
  ],
  "coreFeatures": [
    {
      "title": "Unified Catalog & Category Landing Pages",
      "description": "Combines a sticky-sidebar catalog page (mainpage/product.html) with four dedicated category pages covering 6 Z690 motherboards, 8 RTX 30 series GPUs, 5 PC components, and 3 Intel 12th-Gen gaming laptops.",
      "badge": "Catalog"
    },
    {
      "title": "Interactive Product Image Slideshow",
      "description": "Implements client-side gallery switching via Slide Show.js with Prev/Next controls so users can inspect multiple hardware angles inside every product detail page.",
      "badge": "Interactivity"
    },
    {
      "title": "Explore #AORUS Technical Articles",
      "description": "Publishes seven full-length articles covering Intel 12th-Gen Cinebench/gaming benchmarks, DDR5 and PCIe 5.0 architecture, VisionLINK connectivity, and buyer guides.",
      "badge": "Editorial"
    },
    {
      "title": "Live Digital Clock & Back-to-Top Controls",
      "description": "Renders a real-time date and 12-hour digital clock widget (Digital Clock.js) on the home page and a scroll-threshold Back To Top button (Back To Top.js) across pages.",
      "badge": "UI Widgets"
    },
    {
      "title": "Ambient Video & Custom CSS3 Animations",
      "description": "Uses fixed full-screen MP4 background loops, rainbow gradient dividers, neon text-shadow keyframe pulses, and glitch-hover action buttons without external UI frameworks.",
      "badge": "Visual Design"
    },
    {
      "title": "PHP Product Registration Endpoint",
      "description": "Processes product type, model name, serial number, purchase date, and purchase region via HTTP POST in Product Registration.php and outputs an instant confirmation table.",
      "badge": "Form Handling"
    }
  ],
  "interfaceShowcase": [
    {
      "imageUrl": "/images/projects/aorus_gaming_showcase/image01.webp"
    },
    {
      "imageUrl": "/images/projects/aorus_gaming_showcase/image02.webp"
    },
    {
      "imageUrl": "/images/projects/aorus_gaming_showcase/image03.webp"
    },
    {
      "imageUrl": "/images/projects/aorus_gaming_showcase/image04.webp"
    },
    {
      "imageUrl": "/images/projects/aorus_gaming_showcase/image05.webp"
    },
    {
      "imageUrl": "/images/projects/aorus_gaming_showcase/image06.webp"
    },
    {
      "imageUrl": "/images/projects/aorus_gaming_showcase/image07.webp"
    },
    {
      "imageUrl": "/images/projects/aorus_gaming_showcase/image08.webp"
    }
  ],
  "userFlow": {
    "summary": "Visitors enter the landing portal featuring live time telemetry and category entry cards, browse the sticky-sidebar product catalog or dedicated hardware category pages, inspect multi-image product detail views with slideshows, read benchmark articles, or submit product registration details.",
    "steps": [
      {
        "step": "01",
        "title": "Landing Portal Entry",
        "description": "User loads index.html, observes the live digital clock and embedded AORUS showcase video, and selects a navigation link or one of four Gaming Gears category cards.",
        "actorOrNode": "Home Page"
      },
      {
        "step": "02",
        "title": "Catalog & Category Filtering",
        "description": "User navigates to mainpage/product.html or a dedicated category page under products/ and jumps between Motherboards, Graphics Cards, PC Components, and Gaming Laptops.",
        "actorOrNode": "Catalog View"
      },
      {
        "step": "03",
        "title": "Hardware Spec & Gallery Inspection",
        "description": "User opens a specific hardware page under detail products/, cycles product angles using the Slide Show.js controls, and reviews thermal and performance sections.",
        "actorOrNode": "Product Detail"
      },
      {
        "step": "04",
        "title": "Editorial Reading & Product Registration",
        "description": "User explores benchmark articles in mainpage/explore.html or submits hardware serial and purchase details to mainpage/Product Registration.php for instant POST confirmation.",
        "actorOrNode": "Explore & PHP Form"
      }
    ]
  },
  "systemArchitecture": {
    "summary": "The application follows a lightweight multi-page static web architecture organized into domain folders for main pages, category catalogs, product details, and articles, supported by shared JavaScript DOM modules, responsive CSS3 stylesheets, and a standalone PHP POST form handler.",
    "layers": [
      {
        "name": "Presentation & Page Layer",
        "role": "Serves domain-segmented HTML5 documents across root, mainpage/, products/, detail products/, and article/ directories.",
        "components": ["index.html", "mainpage/*", "products/*", "detail products/*", "article/*"]
      },
      {
        "name": "Styling & Responsive Layer",
        "role": "Provides modular CSS3 Flexbox layouts, custom keyframe animations, and breakpoint rules at 1200px, 992px, 768px, and 480px.",
        "components": ["index_style.css", "product_style.css", "explore_style.css", "detail product *_style.css", "article_style.css"]
      },
      {
        "name": "Client Interaction Layer",
        "role": "Handles DOM state updates for product slideshows, real-time clock ticks, and scroll-to-top visibility via Vanilla JavaScript.",
        "components": ["Slide Show.js", "Digital Clock.js", "Back To Top.js"]
      },
      {
        "name": "Server Form & Media Layer",
        "role": "Processes product registration POST payloads in PHP and serves structured hardware photography, logos, and background MP4 assets from gallery/.",
        "components": ["Product Registration.php", "gallery/"]
      }
    ]
  },
  "databaseDataFlow": {
    "type": "Static Content & Form Flow",
    "summary": "All hardware specifications, editorial articles, and media assets are statically structured across HTML5 pages and the gallery/ asset tree, while Product Registration.php handles transient HTTP POST form submissions in memory without an external database.",
    "entitiesOrPipelines": [
      {
        "name": "HardwareProductPage",
        "type": "Static HTML Entity",
        "fields": ["product_title", "category_slug", "key_features", "core_specs", "slideshow_images", "engineering_sections"]
      },
      {
        "name": "EditorialArticle",
        "type": "Static HTML Entity",
        "fields": ["article_title", "published_date", "hero_image", "youtube_embed", "benchmark_charts"]
      },
      {
        "name": "ProductRegistrationSubmission",
        "type": "PHP POST Payload",
        "fields": ["prodtype", "prodname", "sernum", "purdate", "purreg"]
      }
    ]
  },
  "technicalImplementation": [
    {
      "category": "Client Scripting",
      "title": "Zero-Dependency DOM Slideshow & Clock Engine",
      "description": "Implemented cyclic image indexing in script/Slide Show.js using class-based DOM queries and built a live 12-hour date/time updater in script/Digital Clock.js with custom zero-padding.",
      "badge": "Vanilla JS"
    },
    {
      "category": "CSS3 Engineering",
      "title": "Responsive Flexbox Grids & Keyframe Effects",
      "description": "Authored custom CSS3 keyframe animations (lightson neon header glow and button-49 glitch clip-path transitions) paired with multi-breakpoint media queries down to 480px mobile screens.",
      "badge": "CSS3"
    },
    {
      "category": "Form Processing",
      "title": "Self-Posting PHP Registration Handler",
      "description": "Built mainpage/Product Registration.php using $_SERVER['PHP_SELF'] and isset($_POST['prodname']) to validate submission presence and render a structured HTML confirmation table.",
      "badge": "PHP POST"
    },
    {
      "category": "Asset Organization",
      "title": "Domain-Segmented Asset & Media Pipeline",
      "description": "Structured high-resolution product renders, benchmark charts, brand logos, and looping MP4 background videos inside gallery/ with relative path mapping across nested page depths.",
      "badge": "Media Assets"
    }
  ],
  "primaryTechSpecs": {
    "programmingLanguage": "HTML5 & JavaScript",
    "framework": "CSS3 & PHP",
    "database": "Static Markup"
  },
  "architectureQuality": {
    "badges": [
      "Zero Build Overhead",
      "Responsive Multi-Viewport",
      "Modular CSS Architecture",
      "Clean Asset Hierarchy"
    ]
  }
}
```
