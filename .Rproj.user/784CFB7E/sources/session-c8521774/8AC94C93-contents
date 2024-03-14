#' hello function
#'
#' @description \loadmathjax
#' description of hello function
#'
#'
#' @details
#' Some details
#'
#'
#' @param  name person's name; defaults ot Bob
#'
#'
#' @return
#' Returns a character, name
#'
#'
#' @examples
#' hello("bob")
#'
#'
#' @importFrom stats qt
#' @export
hello <- function(name = "Bob") {
  print(
    paste(
      "Hello, world, and ",
      name,
      "!",
      sep = ""
    )
  )
  return(name)
}


fixrefs <- function() {
  roxygen2::block_get_tag()
  mathjaxr::preview_rd()
}
