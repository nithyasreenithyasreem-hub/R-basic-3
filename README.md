icecream <- data.frame(
      Day = 1:10,
      Temperature = c(28,29,30,31,32,33,34,35,36,37),
      sales = c(120,135,150,165,180,205,230,260,290,320)
    )
  
  plot(
    icecream$Day,
    icecream$sales,
    type = "l",      
    lwd = 2,
    col = "yellow",
    xlab = "Day",
    ylab = "Sales",
    main = "Line Plot of Ice Cream Sales"
  )
  ============================================================================================
    icecream <- data.frame(
      Day = 1:10,
      Temperature = c(28,29,30,31,32,33,34,35,36,37),
      sales = c(120,135,150,165,180,205,230,260,290,320)
    )
  
  barplot(
    icecream$sales,
    names.arg = icecream$Day,
    col = "skyblue",
    xlab = "Day",
    ylab = "Sales",
    main = "Ice Cream Sales Bar Chart"
  )
