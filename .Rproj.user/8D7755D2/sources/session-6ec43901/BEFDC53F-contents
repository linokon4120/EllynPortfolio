# Install devtools (if not already installed)
install.packages("devtools")

# Install portfoliodown
devtools::install_github("business-science/portfoliodown")

# Load portfoliodown
library(portfoliodown)
dir.create("MyPortfolio")     # Create a new directory named "MyPortfolio"
setwd("MyPortfolio")          # Change to the new directory
new_portfolio_site()          # Run the command in the new, empty directory

blogdown::clean_site()
blogdown::serve_site()
blogdown::stop_server()
rmarkdown::render_site()


blogdown::build_site()
