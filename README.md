## Description
☑ A page to list the skills of any given user 
☑ *(If time allows)* when clicking on a particular skill, you can
- show its details related to that user, OR
- show a list of related experiences from that user, OR
- show a list of people who have that same skill, OR
- something else?
☑ A deployed [live]() version of the solution.

### Endpoints
- GET https://torre.bio/api/bios/$username (gets bio information of $username)
- GET https://torre.co/api/opportunities/$id (gets job information of $id)
- POST https://search.torre.co/opportunities/_search/?[offset=$offset&size=$size&aggregate=$aggregate] (search for jobs)
- POST https://search.torre.co/people/_search/?[offset=$offset&size=$size&aggregate=$aggregate] (search for people)

## How to run it locally


1. clone this repo `https://github.com/GustaveRw/Torre-Challenge`

2. cd `Torre-Challenge`

3. Run `npm install`

4.  And run `npm start`

## Author

Jean Marie Gustave Mbonyinshuti

[Genome]()