Project Criteria

Saved at the memory.

```json
{
    id: string,
    title: string,
    createdAt: string,
    updatedAt: string,
    tags: array of string,
    body: string,
}
```

In Example

```json
{
    id: 'notes-V1StGXR8_Z5jdHi6B-myT',
    title: 'Sejarah JavaScript',
    createdAt: '2020-12-23T23:00:09.686Z',
    updatedAt: '2020-12-23T23:00:09.686Z',
    tags: ['NodeJS', 'JavaScript'],
    body: 'JavaScript pertama kali dikembangkan oleh Brendan Eich dari Netscape di bawah nama Mocha, yang nantinya namanya diganti menjadi LiveScript, dan akhirnya menjadi JavaScript. Navigator sebelumnya telah mendukung Java untuk lebih bisa dimanfaatkan para pemrogram yang non-Java.',
},
```

for more info please kindly check in https://www.dicoding.com/academies/342/tutorials/20812

## Using curl to test the API

### POST

```bash
curl -X POST "http://localhost:5555/notes"  \
-d '{"title": "New Stuff", "tags": "actions", "body": "This is the new Stuff"}'
```

### GET

```bash
curl -X GET "http://localhost:5555/notes"
```
