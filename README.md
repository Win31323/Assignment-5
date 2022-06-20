# Assignment-5
creating function with class Rectangle.
# create point class 
class Point:
    # constructor.
    def __init__(self, x, y):
        self.x = x
        self.y = y

  
class Rectangle:

  """A class to manufacture rectangle objects""" 
# constructor.
# which takes posn and w,h parameter.
def __init__(self, posn, M, h):
  """ intialize rectangle at posn, with width M, height n """
   # set value in object.
  self.corner = posn
  self.width
  self.height = h

#str_() methed which will return string format of objects.
def _str_(self):
   return "((0], (1). (2})".format(self.corner, self.width, self.height)
# create rectangle function which will create rectangle of# create point class 
class Point:
    # constructor.
    def __init__(self, x, y):
        self.x = x
        self.y = y

  
class Rectangle:

  """A class to manufacture rectangle objects""" 
# constructor.
# which takes posn and w,h parameter.
def __init__(self, posn, M, h):
  """ intialize rectangle at posn, with width M, height n """
   # set value in object.
  self.corner = posn
  self.width
  self.height = h

#str_() methed which will return string format of objects.
def _str_(self):
   return "((0], (1). (2})".format(self.corner, self.width, self.height)
# create rectangle function which will create rectangle of
# given point x,y corner position and with given width and height.
def create_rectangle(x,y,width, height):
# return object after creation
   return Rectangle(Point(x,y),width,height) 
  
#str rectangle() which return string in format (x, y, width, height)
def str_rectangle(rect):
  return f" ((rect.corner.x], (rect.corner.y), (rect.width), (rect.height))"
  
# shift rectangle() which take rectangle and shift parameter (dx,dy).
def shift_rectangle(rect, dx, dy):
   # add shift para to appropriate place.
  rect.corner.x += dx 
  rect.corner.y += dy

#offset _rectangle() which will return new rectangle with given (dx,dy) offset.
def offset_rectangle(rect, dr, dy):
    # copy rectangle and add offset.
    rect1 = rect
    rect1.corner.x += dx
    rect1.corner.y += dy
    return rect1
  
# testing code.
r1 = create_rectangle(10, 20, 30, 40)
print( str_rectangle(r1))
shift_rectangle(r1, -10, -20)
print( str_rectangle(r1))
r2 = offset_rectangle(r1, 100, 100)
print( str_rectangle(r1))# should be same as previous
print( str_rectangle(r2))
# given point x,y corner position and with given width and height.
def create_rectangle(x,y,width, height):
# return object after creation
   return Rectangle(Point(x,y),width,height) 
  
#str rectangle() which return string in format (x, y, width, height)
def str_rectangle(rect):
  return f" ((rect.corner.x], (rect.corner.y), (rect.width), (rect.height))"
  
# shift rectangle() which take rectangle and shift parameter (dx,dy).
def shift_rectangle(rect, dx, dy):
   # add shift para to appropriate place.
  rect.corner.x += dx 
  rect.corner.y += dy

#offset _rectangle() which will return new rectangle with given (dx,dy) offset.
def offset_rectangle(rect, dr, dy):
    # copy rectangle and add offset.
    rect1 = rect
    rect1.corner.x += dx
    rect1.corner.y += dy
    return rect1
  
# testing code.
r1 = create_rectangle(10, 20, 30, 40)
print( str_rectangle(r1))
shift_rectangle(r1, -10, -20)
print( str_rectangle(r1))
r2 = offset_rectangle(r1, 100, 100)
print( str_rectangle(r1))# should be same as previous
print( str_rectangle(r2))
