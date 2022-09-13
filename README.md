# Storage247

At this point the readme contains only notes and development stuff.

## Todo

- [ ] Show and manage inventory
- [ ] Login
- [ ] Configure categories

## Architecture

### Entities

- User/Account (defined by NextAuth)
  - ID
  - ...
- Item
  - Name (String)
  - Category (String)
  - Box (String)
  - Note (String)
  - Date added (DateTime)
  - Date updated (DateTime)
  - Date deleted (DateTime)
  - User
- Category
  - ID (UUID)
  - Name (String)

### API Endpoints

- [ ] User
- [ ] Item
  - [ ] Create
  - [ ] List
  - [ ] Get one
  - [ ] Update
  - [ ] Delete
- [ ] Category
  - [ ] Create
  - [ ] List
  - [ ] Get one
  - [ ] Update
  - [ ] Delete