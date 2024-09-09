Creating a Dark-Light Mode across the entire application using React Native

---------------------------------------------------------------------------------------------------------

Steps include:
1. Create the context (ThemeContext.tsx)
2. Wrap the entire Tablayout.tsx within the ThemeProvider tags
3. Implent the useTheme across each pages of the application


Modifying a Dropdown from appearing underneath next elements to appearing on top of the elements

--------------------------------------------------------------------------------------------------------

Added
  position: 'relative', 
  zIndex: 1,
  +
  position: 'absolute',
  top: '100%',
  left: 0,
   right: 0,
  zIndex: 1000,
  elevation: 3,
  borderRadius: 8,
  borderBottomColor: '#3B3B3E',
  borderBottomWidth: 1,
  
Eliminated
    marginBottom: 36,



