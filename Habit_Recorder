import requests

TOKEN = "yjhfnpe.kjh47*)l"
USERNAME="marshallfan2021"
user_param = {
    "token": TOKEN,
    "username": USERNAME,
    "agreeTermsOfService": "yes",
    "notMinor": "yes"
}


graph_params={

    "id": "graph1",
    "name": "exerciseDayly",
    "unit": "times/kilos",
    "type": "int",
    "color": "sora"
}
headers = {
   "X-USER-TOKEN":  TOKEN,
}

# user = requests.post("https://pixe.la/v1/users", json=user_param)

# new_graph= requests.post(url="https://pixe.la/v1/users/marshallfan2021/graphs", json=graph_params, headers=headers)

pixel_params = {
    "date": input("what is the date: "),
    "quantity": input("how many times you exercise:"),
    # "optionalData": "{jumping rope:5}"
    }
put_params={
    "name": "exerciseDayly",

             "quantity": "9",
}

new_graph_pixel= requests.post(url="https://pixe.la/v1/users/marshallfan2021/graphs/graph1", json=pixel_params, headers=headers)
# put_graph_pixel= requests.put(url="https://pixe.la/v1/users/marshallfan2021/graphs/graph1/20210509", json=put_params, headers=headers)
# delete_graph_pixel= requests.delete(url="https://pixe.la/v1/users/marshallfan2021/graphs/graph1/20210508",  headers=headers)
# print(delete_graph_pixel.text)
print(new_graph_pixel.text)
# print(put_graph_pixel.text)
