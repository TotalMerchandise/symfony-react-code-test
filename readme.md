# Total Merchandise Symfony + React Code Test

Welcome to the Total Merchandise code test. Your task is to build a page that lists sales staff, shows information and allows searching.

Requirements:
- Create an API endpoint that returns sales staff.
- Fetch and display sales staff using React. You should display all the appropriate information.
- Add the ability to search staff by name. **Please filter your results in your API endpoint.**

You are welcome to add any additional features you see fit.

We recommend you spend no longer than X hours on this test.

## Setup

We have provided a base Symfony + React install.

You will need to run a `composer install` and also an `npm install`. Once installed you can run the server using `symfony server:start`. See [Symfony Install Docs](https://symfony.com/doc/current/setup.html) for more.

Notable docs:

- [Symfony UX React](https://symfony.com/bundles/ux-react/current/index.html)
- [Symfony Encore](https://symfony.com/doc/current/frontend.html#webpack-encore)

The file `default.html.twig` calls a React component found in `assets/react/controllers/Users.jsx`. We recommend you edit the existing `Users.jsx`. For your endpoint you'll need to create this from scratch.

[Axios](https://github.com/axios/axios) is also installed.

## Help

If you are unable to get this project working please get in touch with the recruiter you are working with.

## Mock data

```json
[
  {
    "id": 1,
    "name": "John Smith",
    "quotes": 15,
    "orders": 6,
    "target": 120000,
    "target_progress": 83643
  },
  {
    "id": 2,
    "name": "Alice Johnson",
    "quotes": 28,
    "orders": 9,
    "target": 180000,
    "target_progress": 112567
  },
  {
    "id": 3,
    "name": "Michael Brown",
    "quotes": 7,
    "orders": 3,
    "target": 90000,
    "target_progress": 61234
  },
  {
    "id": 4,
    "name": "Emily Davis",
    "quotes": 20,
    "orders": 8,
    "target": 150000,
    "target_progress": 124502
  },
  {
    "id": 5,
    "name": "David Wilson",
    "quotes": 12,
    "orders": 5,
    "target": 110000,
    "target_progress": 75491
  },
  {
    "id": 6,
    "name": "Jennifer Anderson",
    "quotes": 25,
    "orders": 10,
    "target": 200000,
    "target_progress": 165813
  },
  {
    "id": 7,
    "name": "Robert Martinez",
    "quotes": 18,
    "orders": 7,
    "target": 160000,
    "target_progress": 108995
  },
  {
    "id": 8,
    "name": "Jessica Taylor",
    "quotes": 10,
    "orders": 4,
    "target": 100000,
    "target_progress": 68843
  },
  {
    "id": 9,
    "name": "William Thomas",
    "quotes": 22,
    "orders": 8,
    "target": 170000,
    "target_progress": 133291
  },
  {
    "id": 10,
    "name": "Samantha Hernandez",
    "quotes": 5,
    "orders": 2,
    "target": 70000,
    "target_progress": 34251
  },
  {
    "id": 11,
    "name": "Christopher Perez",
    "quotes": 30,
    "orders": 10,
    "target": 200000,
    "target_progress": 158934
  },
  {
    "id": 12,
    "name": "Amanda Moore",
    "quotes": 3,
    "orders": 1,
    "target": 60000,
    "target_progress": 14356
  },
  {
    "id": 13,
    "name": "Daniel Garcia",
    "quotes": 16,
    "orders": 6,
    "target": 130000,
    "target_progress": 82456
  },
  {
    "id": 14,
    "name": "Elizabeth Rodriguez",
    "quotes": 9,
    "orders": 3,
    "target": 80000,
    "target_progress": 51237
  },
  {
    "id": 15,
    "name": "Matthew Lopez",
    "quotes": 24,
    "orders": 9,
    "target": 190000,
    "target_progress": 145782
  }
]
```