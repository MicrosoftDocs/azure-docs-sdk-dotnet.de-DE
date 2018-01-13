<Type Name="ICertificateOperations" FullName="Microsoft.Azure.Batch.Protocol.ICertificateOperations">
  <TypeSignature Language="C#" Value="public interface ICertificateOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICertificateOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.ICertificateOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICertificateOperations" />
  <TypeSignature Language="F#" Value="type ICertificateOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            CertificateOperations-Vorgänge.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateAddHeaders&gt;&gt; AddWithHttpMessagesAsync (Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter certificate, Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions certificateAddOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CertificateAddHeaders&gt;&gt; AddWithHttpMessagesAsync(class Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter certificate, class Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions certificateAddOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ICertificateOperations.AddWithHttpMessagesAsync(Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter,Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddWithHttpMessagesAsync : Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter * Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateAddHeaders&gt;&gt;" Usage="iCertificateOperations.AddWithHttpMessagesAsync (certificate, certificateAddOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateAddHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="certificate" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter" />
        <Parameter Name="certificateAddOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="certificate">
            Das Zertifikat hinzugefügt werden.
            </param>
        <param name="certificateAddOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Das angegebene Konto hinzugefügt ein Zertifikat.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CancelDeletionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionHeaders&gt;&gt; CancelDeletionWithHttpMessagesAsync (string thumbprintAlgorithm, string thumbprint, Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionOptions certificateCancelDeletionOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionHeaders&gt;&gt; CancelDeletionWithHttpMessagesAsync(string thumbprintAlgorithm, string thumbprint, class Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionOptions certificateCancelDeletionOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ICertificateOperations.CancelDeletionWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CancelDeletionWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionHeaders&gt;&gt;" Usage="iCertificateOperations.CancelDeletionWithHttpMessagesAsync (thumbprintAlgorithm, thumbprint, certificateCancelDeletionOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="certificateCancelDeletionOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="thumbprintAlgorithm">
            Der Algorithmus verwendet, um den fingerabdruckparameter ableiten. Diese Angabe muss sha1.
            </param>
        <param name="thumbprint">
            Der Fingerabdruck des Zertifikats, das gelöscht werden.
            </param>
        <param name="certificateCancelDeletionOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Bricht einen fehlerhaften Löschvorgang eines Zertifikats aus dem angegebenen Konto ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Wenn Sie versuchen, löschen ein Zertifikat, das von einem Pool verwendet wird oder compute-Knoten, ändert den Status des Zertifikats in DeleteFailed aus. Wenn Sie sich entscheiden, dass Sie das Zertifikat weiterhin zu verwenden möchten, können Sie diesen Vorgang verwenden, um den Status des Zertifikats erneut auf aktiv festzulegen. Wenn Sie das Zertifikat löschen möchten, müssen Sie nicht, diesen Vorgang auszuführen, nach dem fehlerhaften Löschvorgang. Sie müssen sicherstellen, dass das Zertifikat nicht von Ressourcen verwendet wird, und klicken Sie dann Sie es beim Löschen des Zertifikats versuchen.
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteHeaders&gt;&gt; DeleteWithHttpMessagesAsync (string thumbprintAlgorithm, string thumbprint, Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteOptions certificateDeleteOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationHeaderResponse`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteHeaders&gt;&gt; DeleteWithHttpMessagesAsync(string thumbprintAlgorithm, string thumbprint, class Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteOptions certificateDeleteOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ICertificateOperations.DeleteWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteHeaders&gt;&gt;" Usage="iCertificateOperations.DeleteWithHttpMessagesAsync (thumbprintAlgorithm, thumbprint, certificateDeleteOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationHeaderResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="certificateDeleteOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="thumbprintAlgorithm">
            Der Algorithmus verwendet, um den fingerabdruckparameter ableiten. Diese Angabe muss sha1.
            </param>
        <param name="thumbprint">
            Der Fingerabdruck des Zertifikats, das gelöscht werden.
            </param>
        <param name="certificateDeleteOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht ein Zertifikat aus dem angegebenen Konto.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Ein Zertifikat kann nicht gelöscht werden, wenn eine Ressource (Pool oder Compute-Knoten) verwendet wird. Bevor Sie ein Zertifikat löschen können, Sie müssen daher sicherstellen, dass das Zertifikat ist nicht mit vorhandenen Pools verknüpft, das Zertifikat ist nicht installiert, auf den Computeknoten (auch wenn Sie ein Zertifikat aus einem Pool entfernen, es nicht entfernt, wird aus vorhandenen Serverknoten in diesem Pool bis Neustart), und keine ausgeführten Tasks richten sich nach dem Zertifikat. Wenn Sie versuchen, ein Zertifikat zu löschen, die verwendet wird, schlägt der Löschvorgang fehl. Der Zertifikatstatus wechselt zu DeleteFailed. "Abbrechen" Zertifikat löschen können Sie den Status erneut auf aktiv festzulegen, wenn Sie sich entscheiden, dass Sie das Zertifikat weiterhin zu verwenden möchten.
            </remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate,Microsoft.Azure.Batch.Protocol.Models.CertificateGetHeaders&gt;&gt; GetWithHttpMessagesAsync (string thumbprintAlgorithm, string thumbprint, Microsoft.Azure.Batch.Protocol.Models.CertificateGetOptions certificateGetOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.Certificate, class Microsoft.Azure.Batch.Protocol.Models.CertificateGetHeaders&gt;&gt; GetWithHttpMessagesAsync(string thumbprintAlgorithm, string thumbprint, class Microsoft.Azure.Batch.Protocol.Models.CertificateGetOptions certificateGetOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ICertificateOperations.GetWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.CertificateGetOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * Microsoft.Azure.Batch.Protocol.Models.CertificateGetOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate, Microsoft.Azure.Batch.Protocol.Models.CertificateGetHeaders&gt;&gt;" Usage="iCertificateOperations.GetWithHttpMessagesAsync (thumbprintAlgorithm, thumbprint, certificateGetOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate,Microsoft.Azure.Batch.Protocol.Models.CertificateGetHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="certificateGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateGetOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="thumbprintAlgorithm">
            Der Algorithmus verwendet, um den fingerabdruckparameter ableiten. Diese Angabe muss sha1.
            </param>
        <param name="thumbprint">
            Der Fingerabdruck des Zertifikats zu erhalten.
            </param>
        <param name="certificateGetOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft Informationen über das angegebene Zertifikat ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;,Microsoft.Azure.Batch.Protocol.Models.CertificateListHeaders&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.CertificateListNextOptions certificateListNextOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;, class Microsoft.Azure.Batch.Protocol.Models.CertificateListHeaders&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.CertificateListNextOptions certificateListNextOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ICertificateOperations.ListNextWithHttpMessagesAsync(System.String,Microsoft.Azure.Batch.Protocol.Models.CertificateListNextOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * Microsoft.Azure.Batch.Protocol.Models.CertificateListNextOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;, Microsoft.Azure.Batch.Protocol.Models.CertificateListHeaders&gt;&gt;" Usage="iCertificateOperations.ListNextWithHttpMessagesAsync (nextPageLink, certificateListNextOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;,Microsoft.Azure.Batch.Protocol.Models.CertificateListHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="certificateListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateListNextOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="certificateListNextOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet alle Zertifikate, die dem angegebenen Konto hinzugefügt wurden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;,Microsoft.Azure.Batch.Protocol.Models.CertificateListHeaders&gt;&gt; ListWithHttpMessagesAsync (Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions certificateListOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;, class Microsoft.Azure.Batch.Protocol.Models.CertificateListHeaders&gt;&gt; ListWithHttpMessagesAsync(class Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions certificateListOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ICertificateOperations.ListWithHttpMessagesAsync(Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;, Microsoft.Azure.Batch.Protocol.Models.CertificateListHeaders&gt;&gt;" Usage="iCertificateOperations.ListWithHttpMessagesAsync (certificateListOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;,Microsoft.Azure.Batch.Protocol.Models.CertificateListHeaders&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="certificateListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="certificateListOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="customHeaders">
            Die Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet alle Zertifikate, die dem angegebenen Konto hinzugefügt wurden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Batch.Protocol.Models.BatchErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>