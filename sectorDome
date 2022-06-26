import time


sector_lists = ["health", "hospitality", "science", "manufacturing", "education", "services", "technology", "trades", "culinary"]


sector_data = {
  "health": "59M (million)",
  "hospitality": "212M (million)", 
  "science": "8.8M (million)",
  "manufacturing": "873M (million)",
  "education": "85M (million)", 
  "services": "1.6B (billion)", 
  "technology": "5.53M (million)",
  "trades": "125M (million)",
  "culinary": "1B (billion)"
}

sector_research = {
  "health": "https://www.investopedia.com/terms/h/health_care_sector.asp",
  
  "hospitality": "https://www.revfine.com/hospitality-sector/", 
  
  "science": "https://www.indeed.com/career-advice/career-development/branches-of-science",
  
  "manufacturing": "https://www.sciencedirect.com/topics/engineering/manufacturing-sector",
  
  "education": "https://www.technofunc.com/index.php/domain-knowledge/education-domain/item/sectors-in-education-industry", 
  
  "services": "https://www.investopedia.com/terms/s/service-sector.asp", 
  
  "technology": "https://www.thebalance.com/what-is-the-technology-sector-5199019",
  
  "trades": "https://sumup.co.uk/business-guide/lg/trades-industry-guide/",
  
  "culinary": "https://www.theculinarypro.com/abouttheindustry"
}

def list_sectors():
  
  print("These are the main sectors:")
  
  counter = 1

  for sector in sector_lists:
    print(str(counter) + ". " + sector)
    
    counter += 1

  print("")



def show_sect_detail():
  print("There are {0} {1} workers".format(sector_data[check_simplify], check_simplify))
  time.sleep(2)
  print("")
  time.sleep(2)


  while True:
    research = input("Do you want to conduct further research on this sector? (Y/N) ")
    
    if research.lower() == "y":
      link = sector_research[check_simplify]
      
      print('- ' + link)

      
      print("")
      print("")
      print("")
      break
  
    elif research.lower() == "n":
      print("")
      print("")
      print("")
      break
  
    else:
      continue





# START PROCESS


list_sectors()
print("Please write the name of the sector you would like to view")
print("Write 'end' if you don't want to view this information anymore")
print("Write 'view' if you would like to view the different sectors you can view again")
print("")
print("")

while True:
  check = input("Which do you want to see? ")
  check_simplify = check.lower()
  
  if check_simplify in sector_lists:

    show_sect_detail()
    

  elif check_simplify == "end":
    break

  elif check_simplify == "view":
    print("")
    print("")
    list_sectors()
    continue
    
  else:
    continue
