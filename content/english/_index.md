---
###################### hero slider ###########################
slider:
  enable : true
  slider_item:
  # slider item loop
  - bg_image : images/service/service-8.png
    animation_from : left
    subtitle : One partner for
    title : IT, Fire & Cleaning
    content : Up to Par Technologies keeps your business up to par with reliable IT networks, certified fire extinguisher services, and professional pressure washing for a clean, safe property.
    pagination_icon : ti-menu-alt # themify icon pack : https://themify.me/themify-icons
    pagination_name : All Services
    button:
      enable : true
      label: View all services
      link : "service/"
      
  # slider item loop
  - bg_image : images/banner/banner-013.jpg
    animation_from : up
    subtitle : Keep your network
    title : Connected & Secure
    content : From structured cabling and clean racks to Wi-Fi, switches, and firewalls, we design and support the network that keeps your business running.
    pagination_icon : ti-server # themify icon pack : https://themify.me/themify-icons
    pagination_name : IT & Networking
    button:
      enable : true
      label: IT & network services
      link : "service/it-service/"

  # slider item loop
  - bg_image : images/banner/banner-012.jpg
    animation_from : down
    subtitle : Protect what matters
    title : Fire Safety & Compliance
    content : Certified fire extinguisher inspection, tagging, recharge, and maintenance to help keep your buildings compliant and your people safer.
    pagination_icon : ti-shield # themify icon pack : https://themify.me/themify-icons
    pagination_name : Fire Safety
    button:
      enable : true
      label: Fire safety services
      link : "service/fire-safety/"
      
  # slider item loop
  - bg_image : images/banner/banner-014.jpeg
    animation_from : right
    subtitle : Make a strong
    title : First Impression
    content : Professional pressure washing for buildings, sidewalks, parking lots, and more, so your property always looks clean and welcoming.
    pagination_icon : ti-shine # themify icon pack : https://themify.me/themify-icons
    pagination_name : Pressure Washing
    button:
      enable : true
      label: Pressure washing services
      link : "service/power-washing/"

  - bg_image : images/banner/banner-015.jpg
    animation_from : left
    subtitle : Industries We Serve
    title : Built For Real-World Workplaces
    content : >
      From medical and dental practices to hospitality, restaurants, non-profits,
      and small businesses, UTP Tech keeps your locations connected, compliant,
      and looking sharp across every site you operate.
    pagination_icon : ti-briefcase # themify icon pack : https://themify.me/themify-icons
    pagination_name : Industries
    button:
      enable : true
      label: Explore industries we serve
      link : "industry/"

  - bg_image : images/banner/contact-us-banner-2.jpg
    animation_from : right
    subtitle : Ready To Talk?
    title : Contact UTP Tech Today
    content : >
      Have a project, inspection deadline, or location that needs attention?
      Reach out to Up To Par Technologies and we’ll help you get your technology,
      fire & life safety, and exterior presentation back up to par.
    pagination_icon : ti-email # themify icon pack : https://themify.me/themify-icons
    pagination_name : Contact Us
    button:
      enable : true
      label: Get in touch
      link : "contact/"

########################################## Service ####################################
service:
  enable : true
  title: "What We Do"
  subtitle: "Solutions That Keep You Up to Par"
  section: "service" # showing items from service section
  # service item comes from "content/service" folder

######################################## About #########################################
about:
  enable : true
  bg_image : "images/background/about-bg.jpg"
  title : "Who We Are"
  content : "Up to Par Technologies is a family-driven company serving Texas businesses with dependable IT, professional structured cabling, certified fire extinguisher services, and high-quality pressure washing. We focus on clean work, honest communication, and long-term relationships."
  # bullet point
  bullet_point:
  - "Managed IT & Network Services"
  - "Structured Cabling & Clean Rack Builds"
  - "Wi-Fi, Switching & Firewall Solutions"
  - "Fire Extinguisher Inspection & Maintenance"
  - "Commercial & Residential Pressure Washing"
  - "Local, Friendly, Family-Oriented Service"
  button:
    enable : true
    label : "Learn more about us"
    link : "about/"

##################################### Skill ##############################################
skill:
  enable : true
  subtitle : Our Expertise
  title : Why Choose Up to Par
  content: At Up to Par Technologies, we combine real-world field experience with enterprise-grade best practices. <br><br> We understand how your network, safety systems, and building exterior all work together to support your business. Our team designs, installs, and supports solutions that are reliable, cleanly executed, and easy to manage as you grow.
  # funfacts
  funfacts :
  - icon : ti-server # themify icon pack : https://themify.me/themify-icons
    title : Networks & Cabling Jobs
    count : 230
    
  - icon : ti-face-smile # themify icon pack : https://themify.me/themify-icons
    title : Satisfied Clients
    count : 789
    
  - icon : ti-thumb-up # themify icon pack : https://themify.me/themify-icons
    title : Properties Cleaned & Protected
    count : 580

  # progressbar
  progressbar : 
  - title : Managed IT & Networking
    progress : 90%
    
  - title : Structured Cabling & Racks
    progress : 95%
    
  - title : Fire Safety & Compliance
    progress : 88%
    
  - title : Pressure Washing & Curb Appeal
    progress : 92%
      
########################################## project ####################################
#project:
  #enable : true
  #title: "Recent Work"
  #subtitle: "Projects That Stay Up to Par"
  #section: "project" # showing items from project section
  # project item comes from "content/project" folder

########################################### Mission ###################################
mission:
  enable : true
  subtitle : Our Goal
  title : Our Mission at Up to Par
  content : Our mission is to keep your business connected, compliant, and looking its best through dependable IT, professional structured cabling, trusted fire safety services, and high-quality pressure washing.
  image : images/banner/banner-011.jpg
  accordion:
  - title : Our Company Mission
    description : We help businesses build a strong technology and safety foundation with reliable networks, clean cabling, and compliant fire extinguisher services, all backed by excellent support.
    
  - title : Our Company Vision
    description : We aim to be the go-to partner for IT, fire safety, and exterior cleaning in our communities, known for our craftsmanship, integrity, and family values.
    
  - title : Our Company Goal
    description : Our goal is to reduce your downtime, improve safety and appearance, and provide clear communication so every decision about your infrastructure feels confident and informed.

##################################### Promo video ####################################
#promo_video:
  #enable : true
  #title : "We Are Always <br> Working To Keep You Up to Par"
  #bg_image : "images/background/promo-video.jpg"
  #video_URL : "https://www.youtube.com/embed/ResipmZmpDU"
  #video_title : "See how we support <br> local businesses."

##################################### call to action #################################
testimonial:
  enable : true
  subtitle : Clients
  title : What Our Clients Say
  image : images/client.png
  testimonial_item :
  - name : Small Business Owner
    content : Up to Par Technologies stabilized our network and cleaned up our cabling. Now our staff works without constant IT headaches.
    designation : Managed IT Client
    
  - name : Facility Manager
    content : Their fire extinguisher service was professional, fast, and clearly documented. We feel much better about our compliance now.
    designation : Fire Safety Client
    
  - name : Property Owner
    content : The pressure washing made a huge difference in how our building looks. They treated our property like it was their own.
    designation : Pressure Washing Client

##################################### call to action #################################
call_to_action:
  enable : true
  bg_image : "images/background/cta.jpg"
  title : "Ready to bring your IT, safety, and curb appeal up to par?"
  button:
    enable : true
    label : "Get a quote"
    link : "contact/"
      
########################################## blog ####################################
#blog:
  #enable : true
  #title: "Company News"
  #subtitle: "Updates From Up to Par"
  #section: "blog"
  # blog item comes from "content/blog" folder
  
################################ clints logo slider ################################
#clients_logo_slider:
  #enable : true
  #client_logos:
  #- logo: "images/client-logo/client-logo-1.png"
    #link: "#"

  #- logo: "images/client-logo/client-logo-2.png"
   # link: "https://examplesite.com"

  #- logo: "images/client-logo/client-logo-3.png"
   # link: "#"

  #- logo: "images/client-logo/client-logo-4.png"
   # link: "https://examplesite.com"

  #- logo: "images/client-logo/client-logo-5.png"
  #  link: "#"

  #- logo: "images/client-logo/client-logo-3.png"
  #  link: "https://examplesite.com"

    
---