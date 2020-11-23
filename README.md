# API Documentation

## Endpoints

### Base Url - `/api`

### Employees

- `GET /employees`
- `GET /employees/:id`
- `POST /employees/:id`
- `DELETE /employees/:id`

#### Model

```ts
interface Employee {
    id: string;
    name: string;
    department: string;
    imgUrl: string;
}
```

### Auth

- `GET /auth`
- `POST /auth`

### Blog

- `GET /blog/:id`
- `POST /blog/:id`
- `DELETE /blog/:id`

## Note

- All slugs like `:id` can be replaced with `:q`, which will then try to match the query with any property.

### Examples

- `/api/employees?q=reinsta` will return the employee `Alois Reinstadler`, since `reinsta` matched `Reinstadler`.

## DEMO

#### VIDEO - [Watch the video](https://drive.google.com/file/d/1A0B3JPUUY2snG8MLZpyz2LWhvThG2epn/view?usp=sharing)

_Video Last Updated on 18th July, 2020_

#### IMAGES

<img src="/demo/images/1.png" width=340px /><img src="/demo/images/2.png" width=340px />
<img src="/demo/images/3.png" width=340px /><img src="/demo/images/4.png" width=340px />
<img src="/demo/images/5.png" width=340px /><img src="/demo/images/6.png" width=340px />
<img src="/demo/images/7.png" width=340px /><img src="/demo/images/8.png" width=340px />
<img src="/demo/images/9.png" width=340px /><img src="/demo/images/10.png" width=340px />
<img src="/demo/images/11.png" width=340px /><img src="/demo/images/12.png" width=340px />
