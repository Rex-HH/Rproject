myString <- "Hello, World!"
print ( myString )
var.1 = c(0, 1, 2, 3)
print(var.1)
var.2 = c("lern", 1)
print(var.2)
var.3 = c(TRUE, 1)
print(var.3)

print(ls())
rm(var.3)
print(ls())

cat("RUNBOOM", file = "./R_test.txt")
cat("cat", file="./R_test.txt", append = TRUE)


sink("./r_test.txt", split=TRUE)
for (i in 1:5)
  print(i)

sink()

sink("./r_test.txt", append = TRUE)
print("RUNBOOM")
sink()

readLines("./R_test.txt")
