# AzReco **Text To Speech** API python example
Sample python script to convert your text to speech with our API. It will generate `.wav` file and play it based given input.

PS.. _We appriciate :star::star::star::star::star: very much :heart_eyes:_

## Supported languages
- AZERBAIJANI (az-AZ)
- TURKISH  (tr-TR)

## Requirements
- You will need first to install [pipenv](https://github.com/pypa/pipenv) as a package management tool
- Clone the project via `git clone` command 
- `pipenv install` command will install all the required libraries


## Usage example:
- To activate environment execute `pipenv shell`
- Execute client.py via correct arguments. Let's see details under the following examples: 
  - For input type _file_ the script uploads `example-tr.txt`, synthesizes speech using our _tr-TR_ text-to-speech and saves the resulting audio as `example-tr.wav` when the synthesizing process finished: `python client.py --input-type file -t text/example-tr.txt -l tr-TR -i api_user_id -k api_token -o example-tr.wav`
  - For input type _text_ the script sends text to the server, synthesizes speech using our _tr-TR_ text-to-speech and saves the resulting audio as `example-tr.wav` when the synthesizing process finished:  `python client.py --input-type text -t "any text" -l tr-TR -i api_user_id -k api_token -o example-tr.wav`  


## Wanna try?
In order to to get **API user id** and **API token**, please send us request via email to info@azreco.az address with the details of motivation and purpose of using it. 