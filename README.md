# Final-Project-Code-1
Advanced function
noun_affixation <- function(noun) {
  if (endsWith(noun, "s")) {
    print("This is a inflectional affix")
  } else if (endsWith(noun, "ed")) {
    print("This is a derivational affix")
  } else {
    print("Noun is in the base form.")
  }
}

word_affixation("potted")
