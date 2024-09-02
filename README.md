
<div align="center">
	<h1>Tema Materia Dark Mpc-Qt</h1>
	<p>
		<b> Tema Materia Dark para el reproductor <a href="https://github.com/mpc-qt/mpc-qt">Media Player Classic Qute Theather</a> basado en <a href="https://ko-fi.com/i/IP5P6TEL5Z">Materia Dark VLC Skin</a></b>.
	</p>
	<br>
</div>


![img_2408201](https://github.com/user-attachments/assets/be7460eb-2db2-468a-bc05-b33785791bf8)


### Instrucciones 
- Descargar <strong>mpc-qt v24.06</strong>
    
  ```
  wget https://github.com/mpc-qt/mpc-qt/archive/refs/tags/v24.06.zip
  ```

- Extraer el archivo `v24.06.zip`

  ```
  unzip v24.06.zip   
  ```
- Clonar este repositorio
  
  ```
    git clone https://github.com/stbn7/materia-dark-mpcqt-theme.git
  ```
- Copiar todo el contenido de la carpeta `basant-materia-dark-mpcqt-skin` dentro de la carpeta `mpc-qt-24.06`

  ```
  cp -r basant-materia-dark-mpcqt-skin/* mpc-qt-24.06/
  ```

- Finalmente, dentro de la carpera `mpc-qt-24.06` abre la terminal y ejecuta los siguientes comandos:

  ```
  qmake6
  make -j`nproc`
  sudo make install
  ```

Probado en KDE neon 6.0 con Qt Version 6.7.2
