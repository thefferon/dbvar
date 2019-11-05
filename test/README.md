# Test HTML Table Rendering on GitHub


<table>
  <thead>
    <tr>
      <th><h3>Supported Features</h3></th>
      <th width="40"><img src="https://raw.github.com/wiki/moxiecode/plupload/Required%20Features/html5.png" title="html5" /></th>
      <th colspan="2"><img src="https://raw.github.com/wiki/moxiecode/plupload/Required%20Features/flash.png" title="flash" /></th>
      <th colspan="2"><img src="https://raw.github.com/wiki/moxiecode/plupload/Required%20Features/silverlight.png" title="silverlight" /></th>
      <th width="40"><img src="https://raw.github.com/wiki/moxiecode/plupload/Required%20Features/html4.png" title="html4" /></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Capability</th>
      <td width="40"><sup>browser</sup></td>
      <td width="40"><sup>browser</sup></td>
      <td width="40"><sup>client&nbsp;</sup></td>
      <td width="40"><sup>browser</sup></td>
      <td width="40"><sup> client </sup></td>
      <td width="40"><sup>browser</sup></td>
    </tr>
    <tr>
      <td>
        <strong>
          access_binary
        </strong> <br />
         <em style="font-size: 0.7em;">
        provide access to raw binary data of the file </em>
      </td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span> <sup><a href="#wiki_fn_1">[1]</a></sup></td>
      <td width="40"><span style="color: red;">✘</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #cc0000;">✘</span> <sup><a href="#wiki_fn_8">[8]</a></sup></td>
    </tr>
    <tr>
      <td>
        <strong>
          access&#95;image&#95;binary
        </strong><br />
        <em style="font-size: 0.7em;">
          provide access to raw binary data of the image
        </em>
      </td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span> <sup><a href="#wiki_fn_1">[1]</a></sup></td>
      <td width="40"><span style="color: #cc0000;">✘</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #cc0000;">✘</span> <sup><a href="#wiki_fn_8">[8]</a></sup></td>
    </tr>
    <tr>
      <td>
        <strong>
          display_media
        </strong><br />
        <em style="font-size: 0.7em;">
        display binary data as thumbs for example </em>
      </td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #cc0000;">✘</span> <sup><a href="#wiki_fn_8">[8]</a></sup></td>
    </tr>
    <tr>
      <td>
        <strong>
          do_cors
        </strong><br />
        <em style="font-size: 0.7em;">
          make cross-domain requests
        </em>
      </td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #cc0000;">✘</span></td>
    </tr>
    <tr>
      <td>
        <strong>
          drag&#95;and&#95;drop
        </strong><br />
        <em style="font-size: 0.7em;">
          accept files dragged and dropped from the desktop
        </em>
      </td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #cc0000;">✘</span></td>
      <td width="40"><span style="color: #cc0000;">✘</span></td>
      <td width="40"><span style="color: #cc0000;">✘</span></td>
      <td width="40"><span style="color: #cc0000;">✘</span></td>
      <td width="40"><span style="color: #cc0000;">✘</span></td>
    </tr>
    <tr>
      <td>
        <strong>
          filter&#95;by&#95;extension
        </strong><br />
        <em style="font-size: 0.7em;">
          filter files in selection dialog by their extensions
        </em>
      </td>
      <td width="40"><span style="color: #006600;">✔</span> <sup><a href="#wiki_fn_7">[7]</a></sup></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span> <sup><a href="#wiki_fn_7">[7]</a></sup></td>
    </tr>
    <tr>
      <td>
        <strong>
          resize_image
        </strong><br />
        <em style="font-size: 0.7em;">
          resize image
        </em>
      </td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span> <sup><a href="#wiki_fn_1">[1]</a></sup></td>
      <td width="40"><span style="color: #cc0000;">✘</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #cc0000;">✘</span></td>
    </tr>
    <tr>
      <td>
        <strong>
          report&#95;upload&#95;progress
        </strong><br />
        <em style="font-size: 0.7em;">
          periodically report how many bytes were uploaded
        </em>
      </td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span> <sup><a href="#wiki_fn_2">[2]</a></sup></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #cc0000;">✘</span></td>
    </tr>
    <tr>
      <td>
        <strong>
          return&#95;response&#95;headers
        </strong><br />
        <em style="font-size: 0.7em;">
          provide access to the headers of http response
        </em>
      </td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #cc0000;">✘</span></td>
      <td width="40"><span style="color: #cc0000;">✘</span></td>
      <td width="40"><span style="color: #cc0000;">✘</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #cc0000;">✘</span></td>
    </tr>
    <tr>
      <td>
        <strong>
          return&#95;response&#95;type
        </strong><br />
        <em style="font-size: 0.7em;">
        support http response of specific type </em>
      </td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span> <sup><a href="#wiki_fn_9">[9]</a></sup></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span> <sup><a href="#wiki_fn_9">[9]</a></sup></td>
    </tr>
    <tr>
      <td>
        <strong>
          return&#95;status&#95;code
        </strong><br />
        <em style="font-size: 0.7em;">
        return http status code of the response </em>
      </td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span> <sup><a href="#wiki_fn_10">[10]</a></sup></td>
      <td width="40"><span style="color: #006600;">✔</span> <sup><a href="#wiki_fn_10">[10]</a></sup></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span> <sup><a href="#wiki_fn_10">[10]</a></sup></td>
    </tr>
    <tr>
      <td>
        <strong>
          send&#95;custom&#95;headers
        </strong> <br />
        <em style="font-size: 0.7em;">
          send custom http header with the request
        </em>
      </td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span> <sup><a href="#wiki_fn_12">[12]</a></sup></td>
      <td width="40"><span style="color: #cc0000;">✘</span></td>
      <td width="40"><span style="color: #cc0000;">✘</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
    </tr>
    <tr>
      <td>
        <strong>
          select_file
        </strong><br />
        <em style="font-size: 0.7em;">
          pick up a files from a dialog
        </em>
      </td>
      <td width="40"><span style="color: #006600;">✔</span> <sup><a href="#wiki_fn_3">[3]</a></sup></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
    </tr>
    <tr>
      <td>
        <strong>
          select_folder
        </strong><br />
        <em style="font-size: 0.7em;">
          select a folder from a dialog
        </em>
      </td>
      <td width="40"><span style="color: #006600;">✔</span> <sup><a href="#wiki_fn_3">[4]</a></sup></td>
      <td width="40"><span style="color: #cc0000;">✘</span></td>
      <td width="40"><span style="color: #cc0000;">✘</span></td>
      <td width="40"><span style="color: #cc0000;">✘</span></td>
      <td width="40"><span style="color: #cc0000;">✘</span></td>
      <td width="40"><span style="color: #cc0000;">✘</span></td>
    </tr>
    <tr>
      <td>
        <strong>
          select_multiple
        </strong><br />
        <em style="font-size: 0.7em;">
        select multiple files at once from a file dialog </em>
      </td>
      <td width="40"><span style="color: #006600;">✔</span> <sup><a href="#wiki_fn_4">[5]</a></sup></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #cc0000;">✘</span></td>
    </tr>
    <tr>
      <td>
        <strong>
          send&#95;binary&#95;string
        </strong><br />
        <em style="font-size: 0.7em;">
          send raw binary data (typically a binary string)
        </em>
      </td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span> <sup><a href="#wiki_fn_1">[1]</a></sup></td>
      <td width="40"><span style="color: #cc0000;">✘</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #cc0000;">✘</span></td>
    </tr>
    <tr>
      <td>
        <strong>
          send&#95;browser&#95;cookies
        </strong><br />
        <em style="font-size: 0.7em;">
        send browser cookies with http request </em>
      </td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #cc0000;">✘</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #cc0000;">✘</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
    </tr>
    <tr>
      <td>
        <strong>
          send_multipart
        </strong> <br />
        <em style="font-size: 0.7em;">
          send multipart/form-data
        </em>
      </td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
    </tr>
    <tr>
      <td>
        <strong>
          slice_blob
        </strong><br />
        <em style="font-size: 0.7em;">
        slice the file or blob </em>
      </td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span> <sup><a href="#wiki_fn_1">[1]</a></sup></td>
      <td width="40"><span style="color: #cc0000;">✘</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #cc0000;">✘</span></td>
    </tr>
    <tr>
      <td>
        <strong>
          stream_upload
        </strong><br />
        <em style="font-size: 0.7em;">
        upload file without preloading it to memory </em>
      </td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #cc0000;">✘</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
    </tr>
    <tr>
      <td>
        <strong>
          summon&#95;file&#95;dialog
        </strong> <br />
        <em style="font-size: 0.7em;">
        programmatically trigger file dialog </em>
      </td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #cc0000;">✘</span></td>
      <td width="40"><span style="color: #cc0000;">✘</span></td>
      <td width="40"><span style="color: #cc0000;">✘</span></td>
      <td width="40"><span style="color: #cc0000;">✘</span></td>
      <td width="40"><span style="color: #006600;">✔</span> <sup><a href="#wiki_fn_6">[6]</a></sup></td>
    </tr>
    <tr>
      <td>
        <strong>
          upload_filesize
        </strong><br />
        <em style="font-size: 0.7em;">upload file of specific size </em>
      </td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span> <sup><a href="#wiki_fn_1">[1]</a></sup></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
    </tr>
      <tr>
      <td>
        <strong>use&#95;http&#95;method
        </strong><br />
        <em style="font-size: 0.7em;">use specific http method</em></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span> <sup><a href="#wiki_fn_11">[11]</a></sup></td>
      <td width="40"><span style="color: #006600;">✔</span> <sup><a href="#wiki_fn_11">[11]</a></sup></td>
      <td width="40"><span style="color: #006600;">✔</span> <sup><a href="#wiki_fn_11">[11]</a></sup></td>
      <td width="40"><span style="color: #006600;">✔</span></td>
      <td width="40"><span style="color: #006600;">✔</span> <sup><a href="#wiki_fn_11">[11]</a></sup></td>
    </tr>
  </tbody>
</table>


FTP Directory: <a href="ftp://ftp.ncbi.nlm.nih.gov/pub/dbVar/sandbox/sv_datasets/nonredundant">nonredundant</a><br />
Last modified: Oct 22, 2019<br />
File types: bed, bedpe, tsv<br />
<h3>
Deletions</h3>
<table>
<tbody>
<tr>
<th>Type and FTP Directory</th>
<th>GRCh37</th>
<th>GRCh38</th>
<tr>
<td>All</td>
<td>2,565,798</td>
<td>2,553,342</td>
</tr>
<tr>
<td>Common</td>
<td>256,543</td>
<td>255,992</td>
</tr>
<tr>
<td>Pathogenic</td>
<td>11,296</td>
<td>11,105</td>
</tr>
<tr>
<td>Somatic</td>
<td>23,360</td>
<td>23,319</td>
</tr>
</tbody>
</table>
<h3>
Duplications</h3>
<table>
<tbody>
<tr>
<th>Type and FTP Directory</th>
<th>GRCh37</th>
<th>GRCh38</th>
<tr>
<td>All</td>
<td>428,103</td>
<td>417,693</td>
</tr>
<tr>
<td>Common</td>
<td>68,992</td>
<td>68,447</td>
</tr>
<tr>
<td>Pathogenic</td>
<td>4,337</td>
<td>4,206</td>
</tr>
<tr>
<td>Somatic</td>
<td>15,103</td>
<td>15,077</td>
</tr>
</tbody>
</table>
<h3>
Insertions</h3>
<table>
<tbody>
<tr>
<th>Type and FTP Directory</th>
<th>GRCh37</th>
<th>GRCh38</th>
<tr>
<td>All</td>
<td>1,322,707</td>
<td>1,327,375</td>
</tr>
<tr>
<td>Common</td>
<td>138,871</td>
<td>138,737</td>
</tr>
<tr>
<td>Pathogenic</td>
<td>71</td>
<td>71</td>
</tr>
<tr>
<td>Somatic</td>
<td>0</td>
<td>0</td>
</tr>
</tbody>
</table>
