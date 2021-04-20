# drew

makeCacheMatrix <- function(x = matrix(sample(1:200,10),4,7)) {
  s <- NULL


  }
  get <- function() 
  setsolve <- function(solve) 
  getsolve <- function() s
  list(set = set, get = get)
}

cacheSolve <- function(x, ...) {
  s <- x$getsolve()
  if(!is.null(s)) {
    return(s)
  }
  data <- x$get()
  s <- solve(data, ...)
end
