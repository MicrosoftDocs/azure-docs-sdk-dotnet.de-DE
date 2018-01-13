<Type Name="CloudBlob" FullName="Microsoft.WindowsAzure.Storage.Blob.CloudBlob">
  <TypeSignature Language="C#" Value="public class CloudBlob : Microsoft.WindowsAzure.Storage.Blob.IListBlobItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudBlob extends System.Object implements class Microsoft.WindowsAzure.Storage.Blob.IListBlobItem" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudBlob&#xA;Implements IListBlobItem" />
  <TypeSignature Language="F#" Value="type CloudBlob = class&#xA;    interface IListBlobItem" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.WindowsAzure.Storage.Blob.IListBlobItem</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Stellt einen Azure-Blob dar. Ein Blob speichert Daten von Text- oder Binärdaten, z. B. Dokumente oder Mediendateien.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudBlob (Uri blobAbsoluteUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri blobAbsoluteUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (blobAbsoluteUri As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Blob.CloudBlob : Uri -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlob" Usage="new Microsoft.WindowsAzure.Storage.Blob.CloudBlob blobAbsoluteUri" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="blobAbsoluteUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="blobAbsoluteUri">Ein <see cref="T:System.Uri" /> , der den absoluten URI zum Blob angibt.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> -Klasse unter Verwendung eines absoluten URIS zum Blob.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudBlob (Uri blobAbsoluteUri, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri blobAbsoluteUri, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.#ctor(System.Uri,Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (blobAbsoluteUri As Uri, credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Blob.CloudBlob : Uri * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlob" Usage="new Microsoft.WindowsAzure.Storage.Blob.CloudBlob (blobAbsoluteUri, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="blobAbsoluteUri" Type="System.Uri" />
        <Parameter Name="credentials" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="blobAbsoluteUri">Ein <see cref="T:System.Uri" /> , der den absoluten URI zum Blob angibt.</param>
        <param name="credentials">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />-Objekt.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> -Klasse unter Verwendung eines absoluten URIS zum Blob.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudBlob (Microsoft.WindowsAzure.Storage.StorageUri blobAbsoluteUri, Nullable&lt;DateTimeOffset&gt; snapshotTime, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.StorageUri blobAbsoluteUri, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshotTime, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.#ctor(Microsoft.WindowsAzure.Storage.StorageUri,System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (blobAbsoluteUri As StorageUri, snapshotTime As Nullable(Of DateTimeOffset), credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Blob.CloudBlob : Microsoft.WindowsAzure.Storage.StorageUri * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlob" Usage="new Microsoft.WindowsAzure.Storage.Blob.CloudBlob (blobAbsoluteUri, snapshotTime, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="blobAbsoluteUri" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
        <Parameter Name="snapshotTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="credentials" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="blobAbsoluteUri">Ein <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.StorageUri" /> , das den absoluten URI zum Blob am primären und sekundären Speicherorte enthält.</param>
        <param name="snapshotTime">Ein <see cref="T:System.DateTimeOffset" /> den Momentaufnahme-Zeitstempel angeben, wenn das Blob eine Momentaufnahme ist.</param>
        <param name="credentials">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />-Objekt.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> -Klasse unter Verwendung eines absoluten URIS zum Blob.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudBlob (Uri blobAbsoluteUri, Nullable&lt;DateTimeOffset&gt; snapshotTime, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri blobAbsoluteUri, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshotTime, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.#ctor(System.Uri,System.Nullable{System.DateTimeOffset},Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (blobAbsoluteUri As Uri, snapshotTime As Nullable(Of DateTimeOffset), credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Blob.CloudBlob : Uri * Nullable&lt;DateTimeOffset&gt; * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlob" Usage="new Microsoft.WindowsAzure.Storage.Blob.CloudBlob (blobAbsoluteUri, snapshotTime, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="blobAbsoluteUri" Type="System.Uri" />
        <Parameter Name="snapshotTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="credentials" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="blobAbsoluteUri">Ein <see cref="T:System.Uri" /> , der den absoluten URI zum Blob angibt.</param>
        <param name="snapshotTime">Ein <see cref="T:System.DateTimeOffset" /> den Momentaufnahme-Zeitstempel angeben, wenn das Blob eine Momentaufnahme ist.</param>
        <param name="credentials">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />-Objekt.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> -Klasse unter Verwendung eines absoluten URIS zum Blob.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AbortCopy">
      <MemberSignature Language="C#" Value="public virtual void AbortCopy (string copyId, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void AbortCopy(string copyId, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.AbortCopy(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member AbortCopy : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.AbortCopy : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudBlob.AbortCopy (copyId, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="copyId" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="copyId">Eine Zeichenfolge, die den Kopiervorgang identifiziert.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt. Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Bricht einen laufenden Blob-Kopiervorgang ab.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AbortCopyAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task AbortCopyAsync (string copyId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AbortCopyAsync(string copyId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.AbortCopyAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function AbortCopyAsync (copyId As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member AbortCopyAsync : string -&gt; System.Threading.Tasks.Task&#xA;override this.AbortCopyAsync : string -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.AbortCopyAsync copyId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="copyId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="copyId">Eine Zeichenfolge, die den Kopiervorgang identifiziert.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Abbrechen eines laufenden Blob-Kopiervorgangs.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AbortCopyAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task AbortCopyAsync (string copyId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AbortCopyAsync(string copyId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.AbortCopyAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AbortCopyAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.AbortCopyAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.AbortCopyAsync (copyId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="copyId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="copyId">Eine Zeichenfolge, die den Kopiervorgang identifiziert.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Abbrechen eines laufenden Blob-Kopiervorgangs.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AbortCopyAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task AbortCopyAsync (string copyId, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AbortCopyAsync(string copyId, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.AbortCopyAsync(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member AbortCopyAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.AbortCopyAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.AbortCopyAsync (copyId, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="copyId" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="copyId">Eine Zeichenfolge, die den Kopiervorgang identifiziert.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Abbrechen eines laufenden Blob-Kopiervorgangs.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AbortCopyAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task AbortCopyAsync (string copyId, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task AbortCopyAsync(string copyId, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.AbortCopyAsync(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AbortCopyAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.AbortCopyAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.AbortCopyAsync (copyId, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="copyId" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="copyId">Eine Zeichenfolge, die den Kopiervorgang identifiziert.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Abbrechen eines laufenden Blob-Kopiervorgangs.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireLease">
      <MemberSignature Language="C#" Value="public virtual string AcquireLease (Nullable&lt;TimeSpan&gt; leaseTime, string proposedLeaseId, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string AcquireLease(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; leaseTime, string proposedLeaseId, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.AcquireLease(System.Nullable{System.TimeSpan},System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member AcquireLease : Nullable&lt;TimeSpan&gt; * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; string&#xA;override this.AcquireLease : Nullable&lt;TimeSpan&gt; * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; string" Usage="cloudBlob.AcquireLease (leaseTime, proposedLeaseId, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="leaseTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="proposedLeaseId" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="leaseTime">Ein <see cref="T:System.TimeSpan" /> auf Sekunden abgerundet, die für die Leasedauer, die werden Zeitspanne darstellt. Wenn <c>null</c>, wird eine unbegrenzte Lease erworben werden. Wenn Sie nicht null ist, dies muss 15 bis 60 Sekunden.</param>
        <param name="proposedLeaseId">Eine Zeichenfolge, die die vorgeschlagene Lease-ID für die neue Leasedauer darstellt oder <c>null</c> , wenn keine Lease-ID vorgeschlagen wird.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt. Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Ruft eine Lease für dieses Blob ab.
            </summary>
        <returns>Die ID der erworbenen Lease.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireLeaseAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; AcquireLeaseAsync (Nullable&lt;TimeSpan&gt; leaseTime, string proposedLeaseId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; AcquireLeaseAsync(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; leaseTime, string proposedLeaseId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.AcquireLeaseAsync(System.Nullable{System.TimeSpan},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function AcquireLeaseAsync (leaseTime As Nullable(Of TimeSpan), Optional proposedLeaseId As String = null) As Task(Of String)" />
      <MemberSignature Language="F#" Value="abstract member AcquireLeaseAsync : Nullable&lt;TimeSpan&gt; * string -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.AcquireLeaseAsync : Nullable&lt;TimeSpan&gt; * string -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlob.AcquireLeaseAsync (leaseTime, proposedLeaseId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="leaseTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="proposedLeaseId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="leaseTime">Ein <see cref="T:System.TimeSpan" /> auf Sekunden abgerundet, die für die Leasedauer, die werden Zeitspanne darstellt. Wenn <c>null</c>, wird eine unbegrenzte Lease erworben werden. Wenn Sie nicht null ist, dies muss 15 bis 60 Sekunden.</param>
        <param name="proposedLeaseId">Eine Zeichenfolge, die die vorgeschlagene Lease-ID für die neue Leasedauer darstellt oder <c>null</c> , wenn keine Lease-ID vorgeschlagen wird.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Abrufen einer Lease für dieses Blob.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Zeichenfolge</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireLeaseAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; AcquireLeaseAsync (Nullable&lt;TimeSpan&gt; leaseTime, string proposedLeaseId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; AcquireLeaseAsync(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; leaseTime, string proposedLeaseId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.AcquireLeaseAsync(System.Nullable{System.TimeSpan},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AcquireLeaseAsync : Nullable&lt;TimeSpan&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.AcquireLeaseAsync : Nullable&lt;TimeSpan&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlob.AcquireLeaseAsync (leaseTime, proposedLeaseId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="leaseTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="proposedLeaseId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="leaseTime">Ein <see cref="T:System.TimeSpan" /> auf Sekunden abgerundet, die für die Leasedauer, die werden Zeitspanne darstellt. Wenn <c>null</c>, wird eine unbegrenzte Lease erworben werden. Wenn Sie nicht null ist, dies muss 15 bis 60 Sekunden.</param>
        <param name="proposedLeaseId">Eine Zeichenfolge, die die vorgeschlagene Lease-ID für die neue Leasedauer darstellt oder <c>null</c> , wenn keine Lease-ID vorgeschlagen wird.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Abrufen einer Lease für dieses Blob.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Zeichenfolge</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireLeaseAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; AcquireLeaseAsync (Nullable&lt;TimeSpan&gt; leaseTime, string proposedLeaseId, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; AcquireLeaseAsync(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; leaseTime, string proposedLeaseId, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.AcquireLeaseAsync(System.Nullable{System.TimeSpan},System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member AcquireLeaseAsync : Nullable&lt;TimeSpan&gt; * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.AcquireLeaseAsync : Nullable&lt;TimeSpan&gt; * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlob.AcquireLeaseAsync (leaseTime, proposedLeaseId, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="leaseTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="proposedLeaseId" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="leaseTime">Ein <see cref="T:System.TimeSpan" /> auf Sekunden abgerundet, die für die Leasedauer, die werden Zeitspanne darstellt. Wenn <c>null</c>, wird eine unbegrenzte Lease erworben werden. Wenn Sie nicht null ist, dies muss 15 bis 60 Sekunden.</param>
        <param name="proposedLeaseId">Eine Zeichenfolge, die die vorgeschlagene Lease-ID für die neue Leasedauer darstellt oder <c>null</c> , wenn keine Lease-ID vorgeschlagen wird.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Abrufen einer Lease für dieses Blob.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Zeichenfolge</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireLeaseAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; AcquireLeaseAsync (Nullable&lt;TimeSpan&gt; leaseTime, string proposedLeaseId, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; AcquireLeaseAsync(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; leaseTime, string proposedLeaseId, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.AcquireLeaseAsync(System.Nullable{System.TimeSpan},System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AcquireLeaseAsync : Nullable&lt;TimeSpan&gt; * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.AcquireLeaseAsync : Nullable&lt;TimeSpan&gt; * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlob.AcquireLeaseAsync (leaseTime, proposedLeaseId, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="leaseTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="proposedLeaseId" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="leaseTime">Ein <see cref="T:System.TimeSpan" /> auf Sekunden abgerundet, die für die Leasedauer, die werden Zeitspanne darstellt. Wenn <c>null</c>, wird eine unbegrenzte Lease erworben werden. Wenn Sie nicht null ist, dies muss 15 bis 60 Sekunden.</param>
        <param name="proposedLeaseId">Eine Zeichenfolge, die die vorgeschlagene Lease-ID für die neue Leasedauer darstellt oder <c>null</c> , wenn keine Lease-ID vorgeschlagen wird.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Abrufen einer Lease für dieses Blob.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Zeichenfolge</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginAbortCopy">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAbortCopy (string copyId, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAbortCopy(string copyId, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginAbortCopy(System.String,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginAbortCopy (copyId As String, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginAbortCopy : string * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginAbortCopy : string * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlob.BeginAbortCopy (copyId, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="copyId" Type="System.String" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="copyId">Eine Zeichenfolge, die den Kopiervorgang identifiziert.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Abbrechen eines laufenden Blob-Kopiervorgangs.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginAbortCopy">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAbortCopy (string copyId, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAbortCopy(string copyId, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginAbortCopy(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginAbortCopy : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginAbortCopy : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlob.BeginAbortCopy (copyId, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="copyId" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="copyId">Eine Zeichenfolge, die den Kopiervorgang identifiziert.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Abbrechen eines laufenden Blob-Kopiervorgangs.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginAcquireLease">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAcquireLease (Nullable&lt;TimeSpan&gt; leaseTime, string proposedLeaseId, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAcquireLease(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; leaseTime, string proposedLeaseId, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginAcquireLease(System.Nullable{System.TimeSpan},System.String,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginAcquireLease (leaseTime As Nullable(Of TimeSpan), proposedLeaseId As String, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginAcquireLease : Nullable&lt;TimeSpan&gt; * string * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginAcquireLease : Nullable&lt;TimeSpan&gt; * string * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlob.BeginAcquireLease (leaseTime, proposedLeaseId, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="leaseTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="proposedLeaseId" Type="System.String" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="leaseTime">Ein <see cref="T:System.TimeSpan" /> auf Sekunden abgerundet, die für die Leasedauer, die werden Zeitspanne darstellt. Wenn <c>null</c>, wird eine unbegrenzte Lease erworben werden. Wenn Sie nicht null ist, dies muss 15 bis 60 Sekunden.</param>
        <param name="proposedLeaseId">Eine Zeichenfolge, die die vorgeschlagene Lease-ID für die neue Leasedauer darstellt oder <c>null</c> , wenn keine Lease-ID vorgeschlagen wird.</param>
        <param name="callback">Eine optionale Rückrufdelegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Abrufen einer Lease für dieses Blob.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginAcquireLease">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAcquireLease (Nullable&lt;TimeSpan&gt; leaseTime, string proposedLeaseId, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginAcquireLease(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; leaseTime, string proposedLeaseId, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginAcquireLease(System.Nullable{System.TimeSpan},System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginAcquireLease : Nullable&lt;TimeSpan&gt; * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginAcquireLease : Nullable&lt;TimeSpan&gt; * string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlob.BeginAcquireLease (leaseTime, proposedLeaseId, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="leaseTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="proposedLeaseId" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="leaseTime">Ein <see cref="T:System.TimeSpan" /> auf Sekunden abgerundet, die für die Leasedauer, die werden Zeitspanne darstellt. Wenn <c>null</c>, wird eine unbegrenzte Lease erworben werden. Wenn Sie nicht null ist, dies muss 15 bis 60 Sekunden.</param>
        <param name="proposedLeaseId">Eine Zeichenfolge, die die vorgeschlagene Lease-ID für die neue Leasedauer darstellt oder <c>null</c> , wenn keine Lease-ID vorgeschlagen wird.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt. Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="callback">Eine optionale Rückrufdelegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Abrufen einer Lease für dieses Blob.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginBreakLease">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginBreakLease (Nullable&lt;TimeSpan&gt; breakPeriod, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginBreakLease(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; breakPeriod, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginBreakLease(System.Nullable{System.TimeSpan},System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginBreakLease (breakPeriod As Nullable(Of TimeSpan), callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginBreakLease : Nullable&lt;TimeSpan&gt; * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginBreakLease : Nullable&lt;TimeSpan&gt; * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlob.BeginBreakLease (breakPeriod, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="breakPeriod" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="breakPeriod">Ein <see cref="T:System.TimeSpan" /> , die die Menge an Zeit, die auf den, Leasedauer auf Sekunden abgerundet darstellt. Wenn <c>null</c>, der Unterbrechungszeitraum ist der Rest der aktuellen Lease oder 0 (null) bei unbegrenzten Leases.</param>
        <param name="callback">Eine optionale Rückrufdelegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Unterbrechen der aktuellen Lease für dieses Blob.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginBreakLease">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginBreakLease (Nullable&lt;TimeSpan&gt; breakPeriod, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginBreakLease(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; breakPeriod, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginBreakLease(System.Nullable{System.TimeSpan},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginBreakLease : Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginBreakLease : Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlob.BeginBreakLease (breakPeriod, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="breakPeriod" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="breakPeriod">Ein <see cref="T:System.TimeSpan" /> , die die Menge an Zeit, die auf den, Leasedauer auf Sekunden abgerundet darstellt. Wenn <c>null</c>, der Unterbrechungszeitraum ist der Rest der aktuellen Lease oder 0 (null) bei unbegrenzten Leases.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt. Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="callback">Eine optionale Rückrufdelegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Unterbrechen der aktuellen Lease für dieses Blob.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginChangeLease">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginChangeLease (string proposedLeaseId, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginChangeLease(string proposedLeaseId, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginChangeLease(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginChangeLease : string * Microsoft.WindowsAzure.Storage.AccessCondition * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginChangeLease : string * Microsoft.WindowsAzure.Storage.AccessCondition * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlob.BeginChangeLease (proposedLeaseId, accessCondition, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="proposedLeaseId" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="proposedLeaseId">Eine Zeichenfolge, die die vorgeschlagene Lease-ID für die neue Leasedauer darstellt. Dies darf nicht null sein.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung, die erfüllt sein muss, damit die Anforderung zu fortfahren, darstellt, einschließlich einer erforderlichen Lease-ID.</param>
        <param name="callback">Eine optionale Rückrufdelegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Ändern der Lease für dieses Blob.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginChangeLease">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginChangeLease (string proposedLeaseId, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginChangeLease(string proposedLeaseId, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginChangeLease(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginChangeLease : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginChangeLease : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlob.BeginChangeLease (proposedLeaseId, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="proposedLeaseId" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="proposedLeaseId">Eine Zeichenfolge, die die vorgeschlagene Lease-ID für die neue Leasedauer darstellt. Dies darf nicht null sein.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung, die erfüllt sein muss, damit die Anforderung zu fortfahren, darstellt, einschließlich einer erforderlichen Lease-ID.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt. Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="callback">Eine optionale Rückrufdelegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Ändern der Lease für dieses Blob.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDelete (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDelete(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginDelete(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginDelete (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginDelete : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDelete : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlob.BeginDelete (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Löschen des BLOBs.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDelete (Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption deleteSnapshotsOption, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDelete(valuetype Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption deleteSnapshotsOption, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginDelete(Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginDelete : Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDelete : Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlob.BeginDelete (deleteSnapshotsOption, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deleteSnapshotsOption" Type="Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="deleteSnapshotsOption">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption" /> Objekt gibt an, ob nur das Blob, um das Blob und alle Momentaufnahmen löschen, löschen oder nur die Momentaufnahmen löschen.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Löschen des BLOBs.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteIfExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteIfExists (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteIfExists(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginDeleteIfExists(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginDeleteIfExists (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteIfExists : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDeleteIfExists : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlob.BeginDeleteIfExists (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Beginnt eine asynchrone Anforderung zum Löschen des BLOBs, wenn sie bereits vorhanden ist.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteIfExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteIfExists (Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption deleteSnapshotsOption, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDeleteIfExists(valuetype Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption deleteSnapshotsOption, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginDeleteIfExists(Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteIfExists : Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDeleteIfExists : Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlob.BeginDeleteIfExists (deleteSnapshotsOption, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deleteSnapshotsOption" Type="Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="deleteSnapshotsOption">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption" /> Objekt gibt an, ob nur das Blob, um das Blob und alle Momentaufnahmen löschen, löschen oder nur die Momentaufnahmen löschen.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Beginnt eine asynchrone Anforderung zum Löschen des BLOBs, wenn sie bereits vorhanden ist.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDownloadRangeToByteArray">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDownloadRangeToByteArray (byte[] target, int index, Nullable&lt;long&gt; blobOffset, Nullable&lt;long&gt; length, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDownloadRangeToByteArray(unsigned int8[] target, int32 index, valuetype System.Nullable`1&lt;int64&gt; blobOffset, valuetype System.Nullable`1&lt;int64&gt; length, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginDownloadRangeToByteArray(System.Byte[],System.Int32,System.Nullable{System.Int64},System.Nullable{System.Int64},System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginDownloadRangeToByteArray (target As Byte(), index As Integer, blobOffset As Nullable(Of Long), length As Nullable(Of Long), callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginDownloadRangeToByteArray : byte[] * int * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDownloadRangeToByteArray : byte[] * int * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlob.BeginDownloadRangeToByteArray (target, index, blobOffset, length, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="target" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="blobOffset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="length" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="target">Das zielbytearray.</param>
        <param name="index">Der Startoffset im Bytearray.</param>
        <param name="blobOffset">Der Startoffset des Datenbereichs in Bytes.</param>
        <param name="length">Die Länge der Daten zum Herunterladen von BLOBs in Byte.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Herunterladen eines Bereichs von Bytes aus einem Blob in ein Bytearray.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDownloadRangeToByteArray">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDownloadRangeToByteArray (byte[] target, int index, Nullable&lt;long&gt; blobOffset, Nullable&lt;long&gt; length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDownloadRangeToByteArray(unsigned int8[] target, int32 index, valuetype System.Nullable`1&lt;int64&gt; blobOffset, valuetype System.Nullable`1&lt;int64&gt; length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginDownloadRangeToByteArray(System.Byte[],System.Int32,System.Nullable{System.Int64},System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginDownloadRangeToByteArray : byte[] * int * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDownloadRangeToByteArray : byte[] * int * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlob.BeginDownloadRangeToByteArray (target, index, blobOffset, length, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="target" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="blobOffset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="length" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="target">Das zielbytearray.</param>
        <param name="index">Der Startoffset im Bytearray.</param>
        <param name="blobOffset">Der Startoffset des Datenbereichs in Bytes.</param>
        <param name="length">Die Länge der Daten zum Herunterladen von BLOBs in Byte.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Herunterladen eines Bereichs von Bytes aus einem Blob in ein Bytearray.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDownloadRangeToStream">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDownloadRangeToStream (System.IO.Stream target, Nullable&lt;long&gt; offset, Nullable&lt;long&gt; length, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDownloadRangeToStream(class System.IO.Stream target, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;int64&gt; length, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginDownloadRangeToStream(System.IO.Stream,System.Nullable{System.Int64},System.Nullable{System.Int64},System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginDownloadRangeToStream (target As Stream, offset As Nullable(Of Long), length As Nullable(Of Long), callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginDownloadRangeToStream : System.IO.Stream * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDownloadRangeToStream : System.IO.Stream * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlob.BeginDownloadRangeToStream (target, offset, length, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="target" Type="System.IO.Stream" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="length" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="target">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Zieldatenstrom darstellt.</param>
        <param name="offset">Der Offset, an dem mit dem Herunterladen der BLOBs in Byte.</param>
        <param name="length">Die Länge der Daten zum Herunterladen von BLOBs in Byte.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Herunterladen eines Bereichs von Bytes aus einem Blob in einen Datenstrom.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDownloadRangeToStream">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDownloadRangeToStream (System.IO.Stream target, Nullable&lt;long&gt; offset, Nullable&lt;long&gt; length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDownloadRangeToStream(class System.IO.Stream target, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;int64&gt; length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginDownloadRangeToStream(System.IO.Stream,System.Nullable{System.Int64},System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginDownloadRangeToStream : System.IO.Stream * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDownloadRangeToStream : System.IO.Stream * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlob.BeginDownloadRangeToStream (target, offset, length, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="target" Type="System.IO.Stream" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="length" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="target">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Zieldatenstrom darstellt.</param>
        <param name="offset">Der Offset, an dem mit dem Herunterladen der BLOBs in Byte.</param>
        <param name="length">Die Länge der Daten zum Herunterladen von BLOBs in Byte.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Herunterladen eines Bereichs von Bytes aus einem Blob in einen Datenstrom.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDownloadToByteArray">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDownloadToByteArray (byte[] target, int index, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDownloadToByteArray(unsigned int8[] target, int32 index, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginDownloadToByteArray(System.Byte[],System.Int32,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginDownloadToByteArray (target As Byte(), index As Integer, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginDownloadToByteArray : byte[] * int * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDownloadToByteArray : byte[] * int * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlob.BeginDownloadToByteArray (target, index, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="target" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="target">Das zielbytearray.</param>
        <param name="index">Der Startoffset im Bytearray.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang, um den Inhalt eines BLOBs in ein Bytearray herunterzuladen.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDownloadToByteArray">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDownloadToByteArray (byte[] target, int index, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDownloadToByteArray(unsigned int8[] target, int32 index, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginDownloadToByteArray(System.Byte[],System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginDownloadToByteArray : byte[] * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDownloadToByteArray : byte[] * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlob.BeginDownloadToByteArray (target, index, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="target" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="target">Das zielbytearray.</param>
        <param name="index">Der Startoffset im Bytearray.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang, um den Inhalt eines BLOBs in ein Bytearray herunterzuladen.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDownloadToFile">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDownloadToFile (string path, System.IO.FileMode mode, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDownloadToFile(string path, valuetype System.IO.FileMode mode, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginDownloadToFile(System.String,System.IO.FileMode,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginDownloadToFile (path As String, mode As FileMode, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginDownloadToFile : string * System.IO.FileMode * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDownloadToFile : string * System.IO.FileMode * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlob.BeginDownloadToFile (path, mode, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="mode" Type="System.IO.FileMode" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="path">Eine Zeichenfolge, die den Pfad zur Zieldatei enthält.</param>
        <param name="mode">Ein <see cref="T:System.IO.FileMode" /> -Enumerationswert ab, der bestimmt, wie die Datei geöffnet oder erstellt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang, um den Inhalt eines BLOBs in eine Datei herunterladen.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDownloadToFile">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDownloadToFile (string path, System.IO.FileMode mode, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDownloadToFile(string path, valuetype System.IO.FileMode mode, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginDownloadToFile(System.String,System.IO.FileMode,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginDownloadToFile : string * System.IO.FileMode * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDownloadToFile : string * System.IO.FileMode * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlob.BeginDownloadToFile (path, mode, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="mode" Type="System.IO.FileMode" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="path">Eine Zeichenfolge, die den Pfad zur Zieldatei enthält.</param>
        <param name="mode">Ein <see cref="T:System.IO.FileMode" /> -Enumerationswert ab, der bestimmt, wie die Datei geöffnet oder erstellt.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang, um den Inhalt eines BLOBs in eine Datei herunterladen.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDownloadToStream">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDownloadToStream (System.IO.Stream target, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDownloadToStream(class System.IO.Stream target, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginDownloadToStream(System.IO.Stream,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginDownloadToStream (target As Stream, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginDownloadToStream : System.IO.Stream * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDownloadToStream : System.IO.Stream * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlob.BeginDownloadToStream (target, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="target" Type="System.IO.Stream" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="target">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Zieldatenstrom darstellt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Herunterladen der Inhalt eines BLOBs in einen Datenstrom.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDownloadToStream">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDownloadToStream (System.IO.Stream target, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginDownloadToStream(class System.IO.Stream target, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginDownloadToStream(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginDownloadToStream : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginDownloadToStream : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlob.BeginDownloadToStream (target, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="target" Type="System.IO.Stream" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="target">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Zieldatenstrom darstellt.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Herunterladen der Inhalt eines BLOBs in einen Datenstrom.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExists (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExists(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginExists(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginExists (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginExists : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginExists : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlob.BeginExists (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Beginnt eine asynchrone Anforderung an das Vorhandensein des BLOBs zu überprüfen.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExists (Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExists(class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginExists(Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginExists : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginExists : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlob.BeginExists (options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Beginnt eine asynchrone Anforderung an das Vorhandensein des BLOBs zu überprüfen.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginFetchAttributes">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginFetchAttributes (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginFetchAttributes(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginFetchAttributes(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginFetchAttributes (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginFetchAttributes : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginFetchAttributes : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlob.BeginFetchAttributes (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Auffüllen von Eigenschaften und Metadaten des BLOBs.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginFetchAttributes">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginFetchAttributes (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginFetchAttributes(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginFetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginFetchAttributes : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginFetchAttributes : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlob.BeginFetchAttributes (accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Auffüllen von Eigenschaften und Metadaten des BLOBs.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginOpenRead">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginOpenRead (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginOpenRead(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginOpenRead(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginOpenRead (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginOpenRead : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginOpenRead : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlob.BeginOpenRead (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Öffnen von eines Datenstroms zum Lesen aus dem Blob.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>
          <para>Auf der <see cref="T:System.IO.Stream" /> zurückgegebenes Objekt die <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.EndOpenRead(System.IAsyncResult)" /> -Methode, die <see cref="M:System.IO.Stream.EndRead(System.IAsyncResult)" /> Methode muss genau einmal aufgerufen werden, für jede <see cref="M:System.IO.Stream.BeginRead(System.Byte[],System.Int32,System.Int32,System.AsyncCallback,System.Object)" /> aufrufen. Wegen eines Fehlers beim Beenden das Lesen Prozess stellen Sie vor Beginn einer anderen lesen verarbeiten kann zu unerwartetem Verhalten führen.</para>
          <para>Beachten Sie, dass diese Methode immer einen Aufruf an sendet die <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginFetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" /> Methode im Hintergrund.</para>
          <para>Legen Sie die <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.StreamMinimumReadSizeInBytes" /> Eigenschaft vor dem Aufrufen dieser Methode zum Angeben der Mindestanzahl von Bytes, die beim Lesen aus dem Datenstrom gepuffert werden sollen. Der Wert muss mindestens 16 KB sein.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginOpenRead">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginOpenRead (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginOpenRead(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginOpenRead(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginOpenRead : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginOpenRead : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlob.BeginOpenRead (accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Öffnen von eines Datenstroms zum Lesen aus dem Blob.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>
          <para>Auf der <see cref="T:System.IO.Stream" /> zurückgegebenes Objekt die <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.EndOpenRead(System.IAsyncResult)" /> -Methode, die <see cref="M:System.IO.Stream.EndRead(System.IAsyncResult)" /> Methode muss genau einmal aufgerufen werden, für jede <see cref="M:System.IO.Stream.BeginRead(System.Byte[],System.Int32,System.Int32,System.AsyncCallback,System.Object)" /> aufrufen. Wegen eines Fehlers beim Beenden das Lesen Prozess stellen Sie vor Beginn einer anderen lesen verarbeiten kann zu unerwartetem Verhalten führen.</para>
          <para>Beachten Sie, dass diese Methode immer einen Aufruf an sendet die <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginFetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" /> Methode im Hintergrund.</para>
          <para>Legen Sie die <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.StreamMinimumReadSizeInBytes" /> Eigenschaft vor dem Aufrufen dieser Methode zum Angeben der Mindestanzahl von Bytes, die beim Lesen aus dem Datenstrom gepuffert werden sollen. Der Wert muss mindestens 16 KB sein.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginReleaseLease">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginReleaseLease (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginReleaseLease(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginReleaseLease(Microsoft.WindowsAzure.Storage.AccessCondition,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginReleaseLease : Microsoft.WindowsAzure.Storage.AccessCondition * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginReleaseLease : Microsoft.WindowsAzure.Storage.AccessCondition * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlob.BeginReleaseLease (accessCondition, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung, die erfüllt sein muss, damit die Anforderung zu fortfahren, darstellt, einschließlich einer erforderlichen Lease-ID.</param>
        <param name="callback">Eine optionale Rückrufdelegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Freigeben der Lease für dieses Blob.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginReleaseLease">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginReleaseLease (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginReleaseLease(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginReleaseLease(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginReleaseLease : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginReleaseLease : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlob.BeginReleaseLease (accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung, die erfüllt sein muss, damit die Anforderung zu fortfahren, darstellt, einschließlich einer erforderlichen Lease-ID.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt. Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="callback">Eine optionale Rückrufdelegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Freigeben der Lease für dieses Blob.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRenewLease">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginRenewLease (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginRenewLease(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginRenewLease(Microsoft.WindowsAzure.Storage.AccessCondition,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginRenewLease : Microsoft.WindowsAzure.Storage.AccessCondition * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginRenewLease : Microsoft.WindowsAzure.Storage.AccessCondition * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlob.BeginRenewLease (accessCondition, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung, die erfüllt sein muss, damit die Anforderung zu fortfahren, darstellt, einschließlich einer erforderlichen Lease-ID.</param>
        <param name="callback">Eine optionale Rückrufdelegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Erneuern einer Lease für dieses Blob.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRenewLease">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginRenewLease (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginRenewLease(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginRenewLease(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginRenewLease : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginRenewLease : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlob.BeginRenewLease (accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung, die erfüllt sein muss, damit die Anforderung zu fortfahren, darstellt, einschließlich einer erforderlichen Lease-ID.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt. Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="callback">Eine optionale Rückrufdelegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Erneuern einer Lease für dieses Blob.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRotateEncryptionKey">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginRotateEncryptionKey (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginRotateEncryptionKey(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginRotateEncryptionKey(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginRotateEncryptionKey (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginRotateEncryptionKey : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginRotateEncryptionKey : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlob.BeginRotateEncryptionKey (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Drehen des Verschlüsselungsschlüssels für dieses Blob.
            Diese Methode wird nur der Schlüsselaustauschschlüssel nicht der CEK gedreht.  Weitere Informationen finden Sie auf https://azure.microsoft.com/en-us/documentation/articles/storage-client-side-encryption/
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>
            Diese Methode hat eine Reihe von Voraussetzungen:
            1. Das Blob muss verschlüsselt sein, für den Dienst mithilfe des Client-seitige ver-(nicht aufseiten des Dienstes Verschlüsselung).
            2. Das lokale Objekt muss die neueste Attribute aus dem Blob für den Dienst verfügen.  Dies kann durch Aufrufen von FetchAttributes() für das Blob oder durch Auflisten der Blobs im Container mit Metadaten erfolgen.
            3. Die Verschlüsselungsrichtlinie auf dem standardmäßigen BlobRequestOptions muss ein IKeyResolver kann zum Auflösen von alten Verschlüsselungsschlüssel enthalten.
            4. Die Verschlüsselungsrichtlinie auf dem standardmäßigen BlobRequestOptions muss ein IKey mit dem neuen Verschlüsselungsschlüssel enthalten.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRotateEncryptionKey">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginRotateEncryptionKey (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginRotateEncryptionKey(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginRotateEncryptionKey(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginRotateEncryptionKey : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginRotateEncryptionKey : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlob.BeginRotateEncryptionKey (accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Für diesen Vorgang, es muss ein <see cref="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfMatchETag" />, <see cref="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfNoneMatchETag" />, <see cref="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfModifiedSinceTime" />, oder <see cref="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfNotModifiedSinceTime" /> Bedingung.  
            Ein <see cref="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfMatchETag" /> intern Bedingung hinzugefügt werden.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Drehen des Verschlüsselungsschlüssels für dieses Blob.
            Diese Methode wird nur der Schlüsselaustauschschlüssel nicht der CEK gedreht.  Weitere Informationen finden Sie auf https://azure.microsoft.com/en-us/documentation/articles/storage-client-side-encryption/
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>
            Diese Methode hat eine Reihe von Voraussetzungen:
            1. Das Blob muss verschlüsselt sein, für den Dienst mithilfe des Client-seitige ver-(nicht aufseiten des Dienstes Verschlüsselung).
            2. Das lokale Objekt muss die neueste Attribute aus dem Blob für den Dienst verfügen.  Dies kann durch Aufrufen von FetchAttributes() für das Blob oder durch Auflisten der Blobs im Container mit Metadaten erfolgen.
            3. Die Verschlüsselungsrichtlinie auf dem standardmäßigen BlobRequestOptions muss ein IKeyResolver kann zum Auflösen von alten Verschlüsselungsschlüssel enthalten.
            4. Die Verschlüsselungsrichtlinie auf dem standardmäßigen BlobRequestOptions muss ein IKey mit dem neuen Verschlüsselungsschlüssel enthalten.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetMetadata">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetMetadata (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetMetadata(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginSetMetadata(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginSetMetadata (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginSetMetadata : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetMetadata : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlob.BeginSetMetadata (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang, um die Metadaten des BLOBs zu aktualisieren.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetMetadata">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetMetadata (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetMetadata(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginSetMetadata(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginSetMetadata : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetMetadata : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlob.BeginSetMetadata (accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang, um die Metadaten des BLOBs zu aktualisieren.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetProperties (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetProperties(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginSetProperties(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginSetProperties (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginSetProperties : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetProperties : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlob.BeginSetProperties (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang, um die Eigenschaften des BLOBs zu aktualisieren.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetProperties (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetProperties(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginSetProperties(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginSetProperties : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetProperties : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlob.BeginSetProperties (accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang, um die Eigenschaften des BLOBs zu aktualisieren.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSnapshot">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSnapshot (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSnapshot(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginSnapshot(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginSnapshot (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginSnapshot : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSnapshot : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlob.BeginSnapshot (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Erstellen einer Momentaufnahme des BLOBs.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSnapshot">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSnapshot (System.Collections.Generic.IDictionary&lt;string,string&gt; metadata, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSnapshot(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; metadata, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginSnapshot(System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginSnapshot : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSnapshot : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlob.BeginSnapshot (metadata, accessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="metadata" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="metadata">Eine Auflistung von Name-Wert-Paare definieren die Metadaten der Momentaufnahme.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt oder <c>null</c>.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Erstellen einer Momentaufnahme des BLOBs.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStartCopy">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginStartCopy (Uri source, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginStartCopy(class System.Uri source, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginStartCopy(System.Uri,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginStartCopy (source As Uri, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginStartCopy : Uri * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginStartCopy : Uri * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlob.BeginStartCopy (source, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.Uri" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="source">Die <see cref="T:System.Uri" /> des Quell-Blob.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Starten des Blob-Inhalte, Eigenschaften und Metadaten in dieses Blob kopiert.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStartCopy">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginStartCopy (Uri source, Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginStartCopy(class System.Uri source, class Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BeginStartCopy(System.Uri,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginStartCopy : Uri * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginStartCopy : Uri * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudBlob.BeginStartCopy (source, sourceAccessCondition, destAccessCondition, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.Uri" />
        <Parameter Name="sourceAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="destAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="source">Die <see cref="T:System.Uri" /> des Quell-Blob.</param>
        <param name="sourceAccessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die zugriffsbedingungen für das Quell-Blob darstellt. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="destAccessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die zugriffsbedingungen für das Ziel-Blob darstellt. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Starten des Blob-Inhalte, Eigenschaften und Metadaten in dieses Blob kopiert.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobType">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.BlobType BlobType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.Blob.BlobType BlobType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BlobType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BlobType As BlobType" />
      <MemberSignature Language="F#" Value="member this.BlobType : Microsoft.WindowsAzure.Storage.Blob.BlobType" Usage="Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BlobType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlobType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Typ des BLOBs ab.
            </summary>
        <value>Ein <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BlobType" />-Enumerationswert.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BreakLease">
      <MemberSignature Language="C#" Value="public virtual TimeSpan BreakLease (Nullable&lt;TimeSpan&gt; breakPeriod = null, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance valuetype System.TimeSpan BreakLease(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; breakPeriod, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BreakLease(System.Nullable{System.TimeSpan},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member BreakLease : Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; TimeSpan&#xA;override this.BreakLease : Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; TimeSpan" Usage="cloudBlob.BreakLease (breakPeriod, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="breakPeriod" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="breakPeriod">Ein <see cref="T:System.TimeSpan" /> , die die Menge an Zeit, die auf den, Leasedauer auf Sekunden abgerundet darstellt. Wenn <c>null</c>, der Unterbrechungszeitraum ist der Rest der aktuellen Lease oder 0 (null) bei unbegrenzten Leases.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt. Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Unterbricht die aktuelle Lease für dieses Blob.
            </summary>
        <returns>Ein <see cref="T:System.TimeSpan" /> , das die Zeitspanne, bevor die Lease, auf dem zweiten endet darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BreakLeaseAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;TimeSpan&gt; BreakLeaseAsync (Nullable&lt;TimeSpan&gt; breakPeriod);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype System.TimeSpan&gt; BreakLeaseAsync(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; breakPeriod) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BreakLeaseAsync(System.Nullable{System.TimeSpan})" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BreakLeaseAsync (breakPeriod As Nullable(Of TimeSpan)) As Task(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member BreakLeaseAsync : Nullable&lt;TimeSpan&gt; -&gt; System.Threading.Tasks.Task&lt;TimeSpan&gt;&#xA;override this.BreakLeaseAsync : Nullable&lt;TimeSpan&gt; -&gt; System.Threading.Tasks.Task&lt;TimeSpan&gt;" Usage="cloudBlob.BreakLeaseAsync breakPeriod" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="breakPeriod" Type="System.Nullable&lt;System.TimeSpan&gt;" />
      </Parameters>
      <Docs>
        <param name="breakPeriod">Ein <see cref="T:System.TimeSpan" /> , die die Menge an Zeit, die auf den, Leasedauer auf Sekunden abgerundet darstellt. Wenn <c>null</c>, der Unterbrechungszeitraum ist der Rest der aktuellen Lease oder 0 (null) bei unbegrenzten Leases.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Unterbrechen der aktuellen Lease für dieses Blob.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:System.TimeSpan" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BreakLeaseAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;TimeSpan&gt; BreakLeaseAsync (Nullable&lt;TimeSpan&gt; breakPeriod, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype System.TimeSpan&gt; BreakLeaseAsync(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; breakPeriod, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BreakLeaseAsync(System.Nullable{System.TimeSpan},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BreakLeaseAsync : Nullable&lt;TimeSpan&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;TimeSpan&gt;&#xA;override this.BreakLeaseAsync : Nullable&lt;TimeSpan&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;TimeSpan&gt;" Usage="cloudBlob.BreakLeaseAsync (breakPeriod, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="breakPeriod" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="breakPeriod">Ein <see cref="T:System.TimeSpan" /> , die die Menge an Zeit, die auf den, Leasedauer auf Sekunden abgerundet darstellt. Wenn <c>null</c>, der Unterbrechungszeitraum ist der Rest der aktuellen Lease oder 0 (null) bei unbegrenzten Leases.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Unterbrechen der aktuellen Lease für dieses Blob.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:System.TimeSpan" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BreakLeaseAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;TimeSpan&gt; BreakLeaseAsync (Nullable&lt;TimeSpan&gt; breakPeriod, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype System.TimeSpan&gt; BreakLeaseAsync(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; breakPeriod, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BreakLeaseAsync(System.Nullable{System.TimeSpan},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member BreakLeaseAsync : Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;TimeSpan&gt;&#xA;override this.BreakLeaseAsync : Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;TimeSpan&gt;" Usage="cloudBlob.BreakLeaseAsync (breakPeriod, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="breakPeriod" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="breakPeriod">Ein <see cref="T:System.TimeSpan" /> , die die Menge an Zeit, die auf den, Leasedauer auf Sekunden abgerundet darstellt. Wenn <c>null</c>, der Unterbrechungszeitraum ist der Rest der aktuellen Lease oder 0 (null) bei unbegrenzten Leases.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Unterbrechen der aktuellen Lease für dieses Blob.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:System.TimeSpan" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BreakLeaseAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;TimeSpan&gt; BreakLeaseAsync (Nullable&lt;TimeSpan&gt; breakPeriod, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;valuetype System.TimeSpan&gt; BreakLeaseAsync(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; breakPeriod, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.BreakLeaseAsync(System.Nullable{System.TimeSpan},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BreakLeaseAsync : Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;TimeSpan&gt;&#xA;override this.BreakLeaseAsync : Nullable&lt;TimeSpan&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;TimeSpan&gt;" Usage="cloudBlob.BreakLeaseAsync (breakPeriod, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="breakPeriod" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="breakPeriod">Ein <see cref="T:System.TimeSpan" /> , die die Menge an Zeit, die auf den, Leasedauer auf Sekunden abgerundet darstellt. Wenn <c>null</c>, der Unterbrechungszeitraum ist der Rest der aktuellen Lease oder 0 (null) bei unbegrenzten Leases.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Unterbrechen der aktuellen Lease für dieses Blob.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:System.TimeSpan" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChangeLease">
      <MemberSignature Language="C#" Value="public virtual string ChangeLease (string proposedLeaseId, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string ChangeLease(string proposedLeaseId, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.ChangeLease(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ChangeLease : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; string&#xA;override this.ChangeLease : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; string" Usage="cloudBlob.ChangeLease (proposedLeaseId, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="proposedLeaseId" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="proposedLeaseId">Eine Zeichenfolge, die die vorgeschlagene Lease-ID für die neue Leasedauer darstellt. Dies darf nicht null sein.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung, die erfüllt sein muss, damit die Anforderung zu fortfahren, darstellt, einschließlich einer erforderlichen Lease-ID.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt. Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Ändert die Lease-ID für dieses Blob.
            </summary>
        <returns>Die neue Lease-ID.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChangeLeaseAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; ChangeLeaseAsync (string proposedLeaseId, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; ChangeLeaseAsync(string proposedLeaseId, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.ChangeLeaseAsync(System.String,Microsoft.WindowsAzure.Storage.AccessCondition)" />
      <MemberSignature Language="F#" Value="abstract member ChangeLeaseAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.ChangeLeaseAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlob.ChangeLeaseAsync (proposedLeaseId, accessCondition)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="proposedLeaseId" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
      </Parameters>
      <Docs>
        <param name="proposedLeaseId">Eine Zeichenfolge, die die vorgeschlagene Lease-ID für die neue Leasedauer darstellt. Dies darf nicht null sein.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung, die erfüllt sein muss, damit die Anforderung zu fortfahren, darstellt, einschließlich einer erforderlichen Lease-ID.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Ändern der Lease für dieses Blob.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Zeichenfolge</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChangeLeaseAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; ChangeLeaseAsync (string proposedLeaseId, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; ChangeLeaseAsync(string proposedLeaseId, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.ChangeLeaseAsync(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ChangeLeaseAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.ChangeLeaseAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlob.ChangeLeaseAsync (proposedLeaseId, accessCondition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="proposedLeaseId" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="proposedLeaseId">Eine Zeichenfolge, die die vorgeschlagene Lease-ID für die neue Leasedauer darstellt. Dies darf nicht null sein.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung, die erfüllt sein muss, damit die Anforderung zu fortfahren, darstellt, einschließlich einer erforderlichen Lease-ID.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Ändern der Lease für dieses Blob.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Zeichenfolge</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChangeLeaseAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; ChangeLeaseAsync (string proposedLeaseId, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; ChangeLeaseAsync(string proposedLeaseId, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.ChangeLeaseAsync(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ChangeLeaseAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.ChangeLeaseAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlob.ChangeLeaseAsync (proposedLeaseId, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="proposedLeaseId" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="proposedLeaseId">Eine Zeichenfolge, die die vorgeschlagene Lease-ID für die neue Leasedauer darstellt. Dies darf nicht null sein.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung, die erfüllt sein muss, damit die Anforderung zu fortfahren, darstellt, einschließlich einer erforderlichen Lease-ID.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Ändern der Lease für dieses Blob.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Zeichenfolge</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChangeLeaseAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; ChangeLeaseAsync (string proposedLeaseId, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; ChangeLeaseAsync(string proposedLeaseId, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.ChangeLeaseAsync(System.String,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ChangeLeaseAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.ChangeLeaseAsync : string * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlob.ChangeLeaseAsync (proposedLeaseId, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="proposedLeaseId" Type="System.String" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="proposedLeaseId">Eine Zeichenfolge, die die vorgeschlagene Lease-ID für die neue Leasedauer darstellt. Dies darf nicht null sein.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung, die erfüllt sein muss, damit die Anforderung zu fortfahren, darstellt, einschließlich einer erforderlichen Lease-ID.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Ändern der Lease für dieses Blob.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Zeichenfolge</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Container">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer Container { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer Container" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.Container" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Container As CloudBlobContainer" />
      <MemberSignature Language="F#" Value="member this.Container : Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" Usage="Microsoft.WindowsAzure.Storage.Blob.CloudBlob.Container" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.Blob.IListBlobItem.Container</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft eine <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" /> Objekt, das die Blob-Container darstellt.
            </summary>
        <value>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" />-Objekt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyState">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.CopyState CopyState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Blob.CopyState CopyState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.CopyState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CopyState As CopyState" />
      <MemberSignature Language="F#" Value="member this.CopyState : Microsoft.WindowsAzure.Storage.Blob.CopyState" Usage="Microsoft.WindowsAzure.Storage.Blob.CloudBlob.CopyState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CopyState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Status des letzten oder ausstehenden Kopiervorgangs ab.
            </summary>
        <value>Ein <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.CopyState" /> Objekt, das den Kopierstatus enthält oder <c>null</c> Wenn kein kopierzustand für das Blob vorhanden ist.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public virtual void Delete (Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption deleteSnapshotsOption = Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption.None, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Delete(valuetype Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption deleteSnapshotsOption, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.Delete(Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Delete : Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.Delete : Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudBlob.Delete (deleteSnapshotsOption, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deleteSnapshotsOption" Type="Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="deleteSnapshotsOption">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption" /> Objekt gibt an, ob nur das Blob, um das Blob und alle Momentaufnahmen löschen, löschen oder nur die Momentaufnahmen löschen.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt. Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Löscht das Blob.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.DeleteAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function DeleteAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteAsync : unit -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.DeleteAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Initiiert einen asynchronen Vorgang zum Löschen des BLOBs.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.DeleteAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.DeleteAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Löschen des BLOBs.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteAsync (Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption deleteSnapshotsOption, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(valuetype Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption deleteSnapshotsOption, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.DeleteAsync(Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteAsync : Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.DeleteAsync (deleteSnapshotsOption, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deleteSnapshotsOption" Type="Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="deleteSnapshotsOption">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption" /> Objekt gibt an, ob nur das Blob, um das Blob und alle Momentaufnahmen löschen, löschen oder nur die Momentaufnahmen löschen.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Löschen des BLOBs.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteAsync (Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption deleteSnapshotsOption, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(valuetype Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption deleteSnapshotsOption, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.DeleteAsync(Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteAsync : Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.DeleteAsync (deleteSnapshotsOption, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deleteSnapshotsOption" Type="Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deleteSnapshotsOption">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption" /> Objekt gibt an, ob nur das Blob, um das Blob und alle Momentaufnahmen löschen, löschen oder nur die Momentaufnahmen löschen.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Löschen des BLOBs.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExists">
      <MemberSignature Language="C#" Value="public virtual bool DeleteIfExists (Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption deleteSnapshotsOption = Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption.None, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool DeleteIfExists(valuetype Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption deleteSnapshotsOption, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.DeleteIfExists(Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExists : Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool&#xA;override this.DeleteIfExists : Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool" Usage="cloudBlob.DeleteIfExists (deleteSnapshotsOption, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deleteSnapshotsOption" Type="Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="deleteSnapshotsOption">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption" /> Objekt gibt an, ob nur das Blob, um das Blob und alle Momentaufnahmen löschen, löschen oder nur die Momentaufnahmen löschen.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt. Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Löscht das Blob an, wenn sie bereits vorhanden ist.
            </summary>
        <returns>
          <c>"true"</c> Wenn das Blob bereits vorhanden war und gelöscht; andernfalls wurde <c>"false"</c>.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteIfExistsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteIfExistsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.DeleteIfExistsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function DeleteIfExistsAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteIfExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudBlob.DeleteIfExistsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Initiiert einen asynchronen Vorgang zum Löschen des BLOBs, wenn sie bereits vorhanden ist.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteIfExistsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteIfExistsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.DeleteIfExistsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteIfExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudBlob.DeleteIfExistsAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Löschen des BLOBs, wenn sie bereits vorhanden ist.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteIfExistsAsync (Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption deleteSnapshotsOption, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteIfExistsAsync(valuetype Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption deleteSnapshotsOption, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.DeleteIfExistsAsync(Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExistsAsync : Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteIfExistsAsync : Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudBlob.DeleteIfExistsAsync (deleteSnapshotsOption, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deleteSnapshotsOption" Type="Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="deleteSnapshotsOption">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption" /> Objekt gibt an, ob nur das Blob, um das Blob und alle Momentaufnahmen löschen, löschen oder nur die Momentaufnahmen löschen.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Löschen des BLOBs, wenn sie bereits vorhanden ist.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteIfExistsAsync (Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption deleteSnapshotsOption, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteIfExistsAsync(valuetype Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption deleteSnapshotsOption, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.DeleteIfExistsAsync(Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExistsAsync : Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteIfExistsAsync : Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudBlob.DeleteIfExistsAsync (deleteSnapshotsOption, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deleteSnapshotsOption" Type="Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deleteSnapshotsOption">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.DeleteSnapshotsOption" /> Objekt gibt an, ob nur das Blob, um das Blob und alle Momentaufnahmen löschen, löschen oder nur die Momentaufnahmen löschen.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Löschen des BLOBs, wenn sie bereits vorhanden ist.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadRangeToByteArray">
      <MemberSignature Language="C#" Value="public virtual int DownloadRangeToByteArray (byte[] target, int index, Nullable&lt;long&gt; blobOffset, Nullable&lt;long&gt; length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 DownloadRangeToByteArray(unsigned int8[] target, int32 index, valuetype System.Nullable`1&lt;int64&gt; blobOffset, valuetype System.Nullable`1&lt;int64&gt; length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.DownloadRangeToByteArray(System.Byte[],System.Int32,System.Nullable{System.Int64},System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DownloadRangeToByteArray : byte[] * int * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; int&#xA;override this.DownloadRangeToByteArray : byte[] * int * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; int" Usage="cloudBlob.DownloadRangeToByteArray (target, index, blobOffset, length, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="target" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="blobOffset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="length" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="target">Das zielbytearray.</param>
        <param name="index">Der Startoffset im Bytearray.</param>
        <param name="blobOffset">Der Startoffset des Datenbereichs in Bytes.</param>
        <param name="length">Die Länge der Daten zum Herunterladen von BLOBs in Byte.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt. Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Lädt einen Bereich von Bytes aus einem Blob in ein Bytearray herunter.
            </summary>
        <returns>Die Gesamtanzahl der in den Puffer gelesenen Bytes.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadRangeToByteArrayAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;int&gt; DownloadRangeToByteArrayAsync (byte[] target, int index, Nullable&lt;long&gt; blobOffset, Nullable&lt;long&gt; length);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int32&gt; DownloadRangeToByteArrayAsync(unsigned int8[] target, int32 index, valuetype System.Nullable`1&lt;int64&gt; blobOffset, valuetype System.Nullable`1&lt;int64&gt; length) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.DownloadRangeToByteArrayAsync(System.Byte[],System.Int32,System.Nullable{System.Int64},System.Nullable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function DownloadRangeToByteArrayAsync (target As Byte(), index As Integer, blobOffset As Nullable(Of Long), length As Nullable(Of Long)) As Task(Of Integer)" />
      <MemberSignature Language="F#" Value="abstract member DownloadRangeToByteArrayAsync : byte[] * int * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; -&gt; System.Threading.Tasks.Task&lt;int&gt;&#xA;override this.DownloadRangeToByteArrayAsync : byte[] * int * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; -&gt; System.Threading.Tasks.Task&lt;int&gt;" Usage="cloudBlob.DownloadRangeToByteArrayAsync (target, index, blobOffset, length)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="target" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="blobOffset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="length" Type="System.Nullable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="target">Das zielbytearray.</param>
        <param name="index">Der Startoffset im Bytearray.</param>
        <param name="blobOffset">Der Startoffset des Datenbereichs in Bytes.</param>
        <param name="length">Die Länge der Daten zum Herunterladen von BLOBs in Byte.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Herunterladen eines Bereichs von Bytes aus einem Blob in ein Bytearray.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Int</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadRangeToByteArrayAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;int&gt; DownloadRangeToByteArrayAsync (byte[] target, int index, Nullable&lt;long&gt; blobOffset, Nullable&lt;long&gt; length, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int32&gt; DownloadRangeToByteArrayAsync(unsigned int8[] target, int32 index, valuetype System.Nullable`1&lt;int64&gt; blobOffset, valuetype System.Nullable`1&lt;int64&gt; length, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.DownloadRangeToByteArrayAsync(System.Byte[],System.Int32,System.Nullable{System.Int64},System.Nullable{System.Int64},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DownloadRangeToByteArrayAsync : byte[] * int * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int&gt;&#xA;override this.DownloadRangeToByteArrayAsync : byte[] * int * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int&gt;" Usage="cloudBlob.DownloadRangeToByteArrayAsync (target, index, blobOffset, length, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="target" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="blobOffset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="length" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="target">Das zielbytearray.</param>
        <param name="index">Der Startoffset im Bytearray.</param>
        <param name="blobOffset">Der Startoffset des Datenbereichs in Bytes.</param>
        <param name="length">Die Länge der Daten zum Herunterladen von BLOBs in Byte.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Herunterladen eines Bereichs von Bytes aus einem Blob in ein Bytearray.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Int</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadRangeToByteArrayAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;int&gt; DownloadRangeToByteArrayAsync (byte[] target, int index, Nullable&lt;long&gt; blobOffset, Nullable&lt;long&gt; length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int32&gt; DownloadRangeToByteArrayAsync(unsigned int8[] target, int32 index, valuetype System.Nullable`1&lt;int64&gt; blobOffset, valuetype System.Nullable`1&lt;int64&gt; length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.DownloadRangeToByteArrayAsync(System.Byte[],System.Int32,System.Nullable{System.Int64},System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DownloadRangeToByteArrayAsync : byte[] * int * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;int&gt;&#xA;override this.DownloadRangeToByteArrayAsync : byte[] * int * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;int&gt;" Usage="cloudBlob.DownloadRangeToByteArrayAsync (target, index, blobOffset, length, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="target" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="blobOffset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="length" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="target">Das zielbytearray.</param>
        <param name="index">Der Startoffset im Bytearray.</param>
        <param name="blobOffset">Der Startoffset des Datenbereichs in Bytes.</param>
        <param name="length">Die Länge der Daten zum Herunterladen von BLOBs in Byte.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Herunterladen eines Bereichs von Bytes aus einem Blob in ein Bytearray.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Int</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadRangeToByteArrayAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;int&gt; DownloadRangeToByteArrayAsync (byte[] target, int index, Nullable&lt;long&gt; blobOffset, Nullable&lt;long&gt; length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int32&gt; DownloadRangeToByteArrayAsync(unsigned int8[] target, int32 index, valuetype System.Nullable`1&lt;int64&gt; blobOffset, valuetype System.Nullable`1&lt;int64&gt; length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.DownloadRangeToByteArrayAsync(System.Byte[],System.Int32,System.Nullable{System.Int64},System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DownloadRangeToByteArrayAsync : byte[] * int * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int&gt;&#xA;override this.DownloadRangeToByteArrayAsync : byte[] * int * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int&gt;" Usage="cloudBlob.DownloadRangeToByteArrayAsync (target, index, blobOffset, length, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="target" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="blobOffset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="length" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="target">Das zielbytearray.</param>
        <param name="index">Der Startoffset im Bytearray.</param>
        <param name="blobOffset">Der Startoffset des Datenbereichs in Bytes.</param>
        <param name="length">Die Länge der Daten zum Herunterladen von BLOBs in Byte.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Herunterladen eines Bereichs von Bytes aus einem Blob in ein Bytearray.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Int</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadRangeToByteArrayAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;int&gt; DownloadRangeToByteArrayAsync (byte[] target, int index, Nullable&lt;long&gt; blobOffset, Nullable&lt;long&gt; length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int32&gt; DownloadRangeToByteArrayAsync(unsigned int8[] target, int32 index, valuetype System.Nullable`1&lt;int64&gt; blobOffset, valuetype System.Nullable`1&lt;int64&gt; length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.IProgress`1&lt;class Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.DownloadRangeToByteArrayAsync(System.Byte[],System.Int32,System.Nullable{System.Int64},System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.IProgress{Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DownloadRangeToByteArrayAsync : byte[] * int * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int&gt;&#xA;override this.DownloadRangeToByteArrayAsync : byte[] * int * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int&gt;" Usage="cloudBlob.DownloadRangeToByteArrayAsync (target, index, blobOffset, length, accessCondition, options, operationContext, progressHandler, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="target" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="blobOffset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="length" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="progressHandler" Type="System.IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="target">Das zielbytearray.</param>
        <param name="index">Der Startoffset im Bytearray.</param>
        <param name="blobOffset">Der Startoffset des Datenbereichs in Bytes.</param>
        <param name="length">Die Länge der Daten zum Herunterladen von BLOBs in Byte.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="progressHandler"> Ein <see cref="T:System.IProgress`1" /> Objekt behandelt <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> Nachrichten.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Herunterladen eines Bereichs von Bytes aus einem Blob in ein Bytearray.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Int</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadRangeToStream">
      <MemberSignature Language="C#" Value="public virtual void DownloadRangeToStream (System.IO.Stream target, Nullable&lt;long&gt; offset, Nullable&lt;long&gt; length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DownloadRangeToStream(class System.IO.Stream target, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;int64&gt; length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.DownloadRangeToStream(System.IO.Stream,System.Nullable{System.Int64},System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DownloadRangeToStream : System.IO.Stream * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.DownloadRangeToStream : System.IO.Stream * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudBlob.DownloadRangeToStream (target, offset, length, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="target" Type="System.IO.Stream" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="length" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="target">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Zieldatenstrom darstellt.</param>
        <param name="offset">Der Offset, an dem mit dem Herunterladen der BLOBs in Byte.</param>
        <param name="length">Die Länge der Daten zum Herunterladen von BLOBs in Byte.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt. Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Lädt einen Bereich von Bytes aus einem Blob in einen Datenstrom herunter.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadRangeToStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DownloadRangeToStreamAsync (System.IO.Stream target, Nullable&lt;long&gt; offset, Nullable&lt;long&gt; length);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DownloadRangeToStreamAsync(class System.IO.Stream target, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;int64&gt; length) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.DownloadRangeToStreamAsync(System.IO.Stream,System.Nullable{System.Int64},System.Nullable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function DownloadRangeToStreamAsync (target As Stream, offset As Nullable(Of Long), length As Nullable(Of Long)) As Task" />
      <MemberSignature Language="F#" Value="abstract member DownloadRangeToStreamAsync : System.IO.Stream * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.DownloadRangeToStreamAsync : System.IO.Stream * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.DownloadRangeToStreamAsync (target, offset, length)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="target" Type="System.IO.Stream" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="length" Type="System.Nullable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="target">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Zieldatenstrom darstellt.</param>
        <param name="offset">Der Offset, an dem mit dem Herunterladen der BLOBs in Byte.</param>
        <param name="length">Die Länge der Daten zum Herunterladen von BLOBs in Byte.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Herunterladen eines Bereichs von Bytes aus einem Blob in einen Datenstrom.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadRangeToStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DownloadRangeToStreamAsync (System.IO.Stream target, Nullable&lt;long&gt; offset, Nullable&lt;long&gt; length, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DownloadRangeToStreamAsync(class System.IO.Stream target, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;int64&gt; length, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.DownloadRangeToStreamAsync(System.IO.Stream,System.Nullable{System.Int64},System.Nullable{System.Int64},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DownloadRangeToStreamAsync : System.IO.Stream * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.DownloadRangeToStreamAsync : System.IO.Stream * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.DownloadRangeToStreamAsync (target, offset, length, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="target" Type="System.IO.Stream" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="length" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="target">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Zieldatenstrom darstellt.</param>
        <param name="offset">Der Offset, an dem mit dem Herunterladen der BLOBs in Byte.</param>
        <param name="length">Die Länge der Daten zum Herunterladen von BLOBs in Byte.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Herunterladen eines Bereichs von Bytes aus einem Blob in einen Datenstrom.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadRangeToStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DownloadRangeToStreamAsync (System.IO.Stream target, Nullable&lt;long&gt; offset, Nullable&lt;long&gt; length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DownloadRangeToStreamAsync(class System.IO.Stream target, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;int64&gt; length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.DownloadRangeToStreamAsync(System.IO.Stream,System.Nullable{System.Int64},System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DownloadRangeToStreamAsync : System.IO.Stream * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.DownloadRangeToStreamAsync : System.IO.Stream * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.DownloadRangeToStreamAsync (target, offset, length, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="target" Type="System.IO.Stream" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="length" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="target">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Zieldatenstrom darstellt.</param>
        <param name="offset">Der Offset, an dem mit dem Herunterladen der BLOBs in Byte.</param>
        <param name="length">Die Länge der Daten zum Herunterladen von BLOBs in Byte.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Herunterladen eines Bereichs von Bytes aus einem Blob in einen Datenstrom.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadRangeToStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DownloadRangeToStreamAsync (System.IO.Stream target, Nullable&lt;long&gt; offset, Nullable&lt;long&gt; length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DownloadRangeToStreamAsync(class System.IO.Stream target, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;int64&gt; length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.DownloadRangeToStreamAsync(System.IO.Stream,System.Nullable{System.Int64},System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DownloadRangeToStreamAsync : System.IO.Stream * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.DownloadRangeToStreamAsync : System.IO.Stream * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.DownloadRangeToStreamAsync (target, offset, length, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="target" Type="System.IO.Stream" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="length" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="target">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Zieldatenstrom darstellt.</param>
        <param name="offset">Der Offset, an dem mit dem Herunterladen der BLOBs in Byte.</param>
        <param name="length">Die Länge der Daten zum Herunterladen von BLOBs in Byte.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Herunterladen eines Bereichs von Bytes aus einem Blob in einen Datenstrom.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadRangeToStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DownloadRangeToStreamAsync (System.IO.Stream target, Nullable&lt;long&gt; offset, Nullable&lt;long&gt; length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DownloadRangeToStreamAsync(class System.IO.Stream target, valuetype System.Nullable`1&lt;int64&gt; offset, valuetype System.Nullable`1&lt;int64&gt; length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.IProgress`1&lt;class Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.DownloadRangeToStreamAsync(System.IO.Stream,System.Nullable{System.Int64},System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.IProgress{Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DownloadRangeToStreamAsync : System.IO.Stream * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.DownloadRangeToStreamAsync : System.IO.Stream * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.DownloadRangeToStreamAsync (target, offset, length, accessCondition, options, operationContext, progressHandler, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="target" Type="System.IO.Stream" />
        <Parameter Name="offset" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="length" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="progressHandler" Type="System.IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="target">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Zieldatenstrom darstellt.</param>
        <param name="offset">Der Offset, an dem mit dem Herunterladen der BLOBs in Byte.</param>
        <param name="length">Die Länge der Daten zum Herunterladen von BLOBs in Byte.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="progressHandler"> Ein <see cref="T:System.IProgress`1" /> Objekt behandelt <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> Nachrichten.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Herunterladen eines Bereichs von Bytes aus einem Blob in einen Datenstrom.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadToByteArray">
      <MemberSignature Language="C#" Value="public virtual int DownloadToByteArray (byte[] target, int index, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 DownloadToByteArray(unsigned int8[] target, int32 index, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.DownloadToByteArray(System.Byte[],System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DownloadToByteArray : byte[] * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; int&#xA;override this.DownloadToByteArray : byte[] * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; int" Usage="cloudBlob.DownloadToByteArray (target, index, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="target" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="target">Das zielbytearray.</param>
        <param name="index">Der Startoffset im Bytearray.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt. Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Lädt den Inhalt eines BLOBs in ein Bytearray herunter.
            </summary>
        <returns>Die Gesamtanzahl der in den Puffer gelesenen Bytes.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadToByteArrayAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;int&gt; DownloadToByteArrayAsync (byte[] target, int index);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int32&gt; DownloadToByteArrayAsync(unsigned int8[] target, int32 index) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.DownloadToByteArrayAsync(System.Byte[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function DownloadToByteArrayAsync (target As Byte(), index As Integer) As Task(Of Integer)" />
      <MemberSignature Language="F#" Value="abstract member DownloadToByteArrayAsync : byte[] * int -&gt; System.Threading.Tasks.Task&lt;int&gt;&#xA;override this.DownloadToByteArrayAsync : byte[] * int -&gt; System.Threading.Tasks.Task&lt;int&gt;" Usage="cloudBlob.DownloadToByteArrayAsync (target, index)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="target" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="target">Das zielbytearray.</param>
        <param name="index">Der Startoffset im Bytearray.</param>
        <summary>
            Initiiert einen asynchronen Vorgang, um den Inhalt eines BLOBs in ein Bytearray herunterzuladen.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Int</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadToByteArrayAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;int&gt; DownloadToByteArrayAsync (byte[] target, int index, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int32&gt; DownloadToByteArrayAsync(unsigned int8[] target, int32 index, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.DownloadToByteArrayAsync(System.Byte[],System.Int32,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DownloadToByteArrayAsync : byte[] * int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int&gt;&#xA;override this.DownloadToByteArrayAsync : byte[] * int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int&gt;" Usage="cloudBlob.DownloadToByteArrayAsync (target, index, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="target" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="target">Das zielbytearray.</param>
        <param name="index">Der Startoffset im Bytearray.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang, um den Inhalt eines BLOBs in ein Bytearray herunterzuladen.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Int</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadToByteArrayAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;int&gt; DownloadToByteArrayAsync (byte[] target, int index, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int32&gt; DownloadToByteArrayAsync(unsigned int8[] target, int32 index, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.DownloadToByteArrayAsync(System.Byte[],System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DownloadToByteArrayAsync : byte[] * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;int&gt;&#xA;override this.DownloadToByteArrayAsync : byte[] * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;int&gt;" Usage="cloudBlob.DownloadToByteArrayAsync (target, index, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="target" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="target">Das zielbytearray.</param>
        <param name="index">Der Startoffset im Bytearray.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang, um den Inhalt eines BLOBs in ein Bytearray herunterzuladen.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Int</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadToByteArrayAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;int&gt; DownloadToByteArrayAsync (byte[] target, int index, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int32&gt; DownloadToByteArrayAsync(unsigned int8[] target, int32 index, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.DownloadToByteArrayAsync(System.Byte[],System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DownloadToByteArrayAsync : byte[] * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int&gt;&#xA;override this.DownloadToByteArrayAsync : byte[] * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int&gt;" Usage="cloudBlob.DownloadToByteArrayAsync (target, index, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="target" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="target">Das zielbytearray.</param>
        <param name="index">Der Startoffset im Bytearray.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang, um den Inhalt eines BLOBs in ein Bytearray herunterzuladen.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Int</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadToByteArrayAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;int&gt; DownloadToByteArrayAsync (byte[] target, int index, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int32&gt; DownloadToByteArrayAsync(unsigned int8[] target, int32 index, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.IProgress`1&lt;class Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.DownloadToByteArrayAsync(System.Byte[],System.Int32,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.IProgress{Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DownloadToByteArrayAsync : byte[] * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int&gt;&#xA;override this.DownloadToByteArrayAsync : byte[] * int * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int&gt;" Usage="cloudBlob.DownloadToByteArrayAsync (target, index, accessCondition, options, operationContext, progressHandler, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="target" Type="System.Byte[]" />
        <Parameter Name="index" Type="System.Int32" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="progressHandler" Type="System.IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="target">Das zielbytearray.</param>
        <param name="index">Der Startoffset im Bytearray.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="progressHandler"> Ein <see cref="T:System.IProgress`1" /> Objekt behandelt <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> Nachrichten.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang, um den Inhalt eines BLOBs in ein Bytearray herunterzuladen.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Int</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadToFile">
      <MemberSignature Language="C#" Value="public virtual void DownloadToFile (string path, System.IO.FileMode mode, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DownloadToFile(string path, valuetype System.IO.FileMode mode, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.DownloadToFile(System.String,System.IO.FileMode,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DownloadToFile : string * System.IO.FileMode * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.DownloadToFile : string * System.IO.FileMode * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudBlob.DownloadToFile (path, mode, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="mode" Type="System.IO.FileMode" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="path">Eine Zeichenfolge, die den Pfad zur Zieldatei enthält.</param>
        <param name="mode">Ein <see cref="T:System.IO.FileMode" /> -Enumerationswert ab, der bestimmt, wie die Datei geöffnet oder erstellt.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt. Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Lädt den Inhalt eines BLOBs in eine Datei herunter.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadToFileAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DownloadToFileAsync (string path, System.IO.FileMode mode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DownloadToFileAsync(string path, valuetype System.IO.FileMode mode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.DownloadToFileAsync(System.String,System.IO.FileMode)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function DownloadToFileAsync (path As String, mode As FileMode) As Task" />
      <MemberSignature Language="F#" Value="abstract member DownloadToFileAsync : string * System.IO.FileMode -&gt; System.Threading.Tasks.Task&#xA;override this.DownloadToFileAsync : string * System.IO.FileMode -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.DownloadToFileAsync (path, mode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="mode" Type="System.IO.FileMode" />
      </Parameters>
      <Docs>
        <param name="path">Eine Zeichenfolge, die den Pfad zur Zieldatei enthält.</param>
        <param name="mode">Ein <see cref="T:System.IO.FileMode" /> -Enumerationswert ab, der bestimmt, wie die Datei geöffnet oder erstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang, um den Inhalt eines BLOBs in eine Datei herunterladen.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadToFileAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DownloadToFileAsync (string path, System.IO.FileMode mode, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DownloadToFileAsync(string path, valuetype System.IO.FileMode mode, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.DownloadToFileAsync(System.String,System.IO.FileMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DownloadToFileAsync : string * System.IO.FileMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.DownloadToFileAsync : string * System.IO.FileMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.DownloadToFileAsync (path, mode, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="mode" Type="System.IO.FileMode" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">Eine Zeichenfolge, die den Pfad zur Zieldatei enthält.</param>
        <param name="mode">Ein <see cref="T:System.IO.FileMode" /> -Enumerationswert ab, der bestimmt, wie die Datei geöffnet oder erstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang, um den Inhalt eines BLOBs in eine Datei herunterladen.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadToFileAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DownloadToFileAsync (string path, System.IO.FileMode mode, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DownloadToFileAsync(string path, valuetype System.IO.FileMode mode, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.DownloadToFileAsync(System.String,System.IO.FileMode,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DownloadToFileAsync : string * System.IO.FileMode * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.DownloadToFileAsync : string * System.IO.FileMode * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.DownloadToFileAsync (path, mode, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="mode" Type="System.IO.FileMode" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="path">Eine Zeichenfolge, die den Pfad zur Zieldatei enthält.</param>
        <param name="mode">Ein <see cref="T:System.IO.FileMode" /> -Enumerationswert ab, der bestimmt, wie die Datei geöffnet oder erstellt.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang, um den Inhalt eines BLOBs in eine Datei herunterladen.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadToFileAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DownloadToFileAsync (string path, System.IO.FileMode mode, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DownloadToFileAsync(string path, valuetype System.IO.FileMode mode, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.DownloadToFileAsync(System.String,System.IO.FileMode,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DownloadToFileAsync : string * System.IO.FileMode * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.DownloadToFileAsync : string * System.IO.FileMode * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.DownloadToFileAsync (path, mode, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="mode" Type="System.IO.FileMode" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">Eine Zeichenfolge, die den Pfad zur Zieldatei enthält.</param>
        <param name="mode">Ein <see cref="T:System.IO.FileMode" /> -Enumerationswert ab, der bestimmt, wie die Datei geöffnet oder erstellt.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang, um den Inhalt eines BLOBs in eine Datei herunterladen.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadToFileAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DownloadToFileAsync (string path, System.IO.FileMode mode, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DownloadToFileAsync(string path, valuetype System.IO.FileMode mode, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.IProgress`1&lt;class Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.DownloadToFileAsync(System.String,System.IO.FileMode,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.IProgress{Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DownloadToFileAsync : string * System.IO.FileMode * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.DownloadToFileAsync : string * System.IO.FileMode * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.DownloadToFileAsync (path, mode, accessCondition, options, operationContext, progressHandler, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="mode" Type="System.IO.FileMode" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="progressHandler" Type="System.IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">Eine Zeichenfolge, die den Pfad zur Zieldatei enthält.</param>
        <param name="mode">Ein <see cref="T:System.IO.FileMode" /> -Enumerationswert ab, der bestimmt, wie die Datei geöffnet oder erstellt.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="progressHandler"> Ein <see cref="T:System.IProgress`1" /> Objekt behandelt <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> Nachrichten.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang, um den Inhalt eines BLOBs in eine Datei herunterladen.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadToFileParallelAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DownloadToFileParallelAsync (string path, System.IO.FileMode mode, int parallelIOCount, Nullable&lt;long&gt; rangeSizeInBytes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DownloadToFileParallelAsync(string path, valuetype System.IO.FileMode mode, int32 parallelIOCount, valuetype System.Nullable`1&lt;int64&gt; rangeSizeInBytes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.DownloadToFileParallelAsync(System.String,System.IO.FileMode,System.Int32,System.Nullable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function DownloadToFileParallelAsync (path As String, mode As FileMode, parallelIOCount As Integer, rangeSizeInBytes As Nullable(Of Long)) As Task" />
      <MemberSignature Language="F#" Value="abstract member DownloadToFileParallelAsync : string * System.IO.FileMode * int * Nullable&lt;int64&gt; -&gt; System.Threading.Tasks.Task&#xA;override this.DownloadToFileParallelAsync : string * System.IO.FileMode * int * Nullable&lt;int64&gt; -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.DownloadToFileParallelAsync (path, mode, parallelIOCount, rangeSizeInBytes)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="mode" Type="System.IO.FileMode" />
        <Parameter Name="parallelIOCount" Type="System.Int32" />
        <Parameter Name="rangeSizeInBytes" Type="System.Nullable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="path">Eine Zeichenfolge, die den Pfad zur Zieldatei enthält.</param>
        <param name="mode">Ein <see cref="T:System.IO.FileMode" /> -Enumerationswert ab, der bestimmt, wie die Datei geöffnet oder erstellt.</param>
        <param name="parallelIOCount">Die maximale Anzahl von Bereichen, die gleichzeitig heruntergeladen werden können</param>
        <param name="rangeSizeInBytes">Die Größe jedes einzelnen Bereichs in Bytes, die parallel gedownloadet wird.
            Die Bereichsgröße muss ein Vielfaches von 4 KB und mindestens 4 MB sein. 16 MB wird verwendet, wenn kein Wert den Standardwert übergeben wird oder 4MB bei transaktionalen MD5 aktiviert ist.</param>
        <summary>
            Initiiert einen asynchronen Vorgang, um den Inhalt eines BLOBs in eine Datei herunterzuladen, durch parallele Anforderungen an.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
            Abhängig von der CPU, Arbeitsspeicher und Bandbreite sollte die ParallelIOCount und RangeSizeInBytes angepasst werden.
            Diese API sollte nur für größere Downloads, wie eine HEAD-Anforderung erfolgt vor dem Herunterladen von Daten verwendet werden.
            Verwenden Sie DownloadToFileAsync() für kleinere Blobs.
            Um die optimale Leistung zu erhalten, wird empfohlen, versuchen Sie es mehreren Werten und Durchsatz zu messen.
            Eine Position, an dem wäre die ParallelIOCount auf die Anzahl der CPUs festgelegt.
            Klicken Sie dann passen Sie die RangeSizeInBytes so an, dass ParallelIOCount Zeiten RangeSizeInBytes der Menge des Arbeitsspeichers an, dass den Prozess entspricht genutzt werden soll.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadToFileParallelAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DownloadToFileParallelAsync (string path, System.IO.FileMode mode, int parallelIOCount, Nullable&lt;long&gt; rangeSizeInBytes, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DownloadToFileParallelAsync(string path, valuetype System.IO.FileMode mode, int32 parallelIOCount, valuetype System.Nullable`1&lt;int64&gt; rangeSizeInBytes, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.DownloadToFileParallelAsync(System.String,System.IO.FileMode,System.Int32,System.Nullable{System.Int64},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DownloadToFileParallelAsync : string * System.IO.FileMode * int * Nullable&lt;int64&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.DownloadToFileParallelAsync : string * System.IO.FileMode * int * Nullable&lt;int64&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.DownloadToFileParallelAsync (path, mode, parallelIOCount, rangeSizeInBytes, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="mode" Type="System.IO.FileMode" />
        <Parameter Name="parallelIOCount" Type="System.Int32" />
        <Parameter Name="rangeSizeInBytes" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">Eine Zeichenfolge, die den Pfad zur Zieldatei enthält.</param>
        <param name="mode">Ein <see cref="T:System.IO.FileMode" /> -Enumerationswert ab, der bestimmt, wie die Datei geöffnet oder erstellt.</param>
        <param name="parallelIOCount">Die maximale Anzahl von Bereichen, die gleichzeitig heruntergeladen werden können.</param>
        <param name="rangeSizeInBytes">Die Größe jedes einzelnen Bereichs in Bytes, die parallel gedownloadet wird.
            Die Bereichsgröße muss ein Vielfaches von 4 KB und mindestens 4 MB sein. 16 MB wird verwendet, wenn kein Wert den Standardwert übergeben wird oder 4MB bei transaktionalen MD5 aktiviert ist.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang, um den Inhalt eines BLOBs in eine Datei herunterzuladen, durch parallele Anforderungen an.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
            Abhängig von der CPU, Arbeitsspeicher und Bandbreite sollte die ParallelIOCount und RangeSizeInBytes angepasst werden.
            Diese API sollte nur für größere Downloads, wie eine HEAD-Anforderung erfolgt vor dem Herunterladen von Daten verwendet werden.
            Verwenden Sie DownloadToFileAsync() für kleinere Blobs.
            Um die optimale Leistung zu erhalten, wird empfohlen, versuchen Sie es mehreren Werten und Durchsatz zu messen.
            Eine Position, an dem wäre die ParallelIOCount auf die Anzahl der CPUs festgelegt.
            Klicken Sie dann passen Sie die RangeSizeInBytes so an, dass ParallelIOCount Zeiten RangeSizeInBytes der Menge des Arbeitsspeichers an, dass den Prozess entspricht genutzt werden soll.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadToFileParallelAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DownloadToFileParallelAsync (string path, System.IO.FileMode mode, int parallelIOCount, Nullable&lt;long&gt; rangeSizeInBytes, long offset, Nullable&lt;long&gt; length, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DownloadToFileParallelAsync(string path, valuetype System.IO.FileMode mode, int32 parallelIOCount, valuetype System.Nullable`1&lt;int64&gt; rangeSizeInBytes, int64 offset, valuetype System.Nullable`1&lt;int64&gt; length, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.DownloadToFileParallelAsync(System.String,System.IO.FileMode,System.Int32,System.Nullable{System.Int64},System.Int64,System.Nullable{System.Int64},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DownloadToFileParallelAsync : string * System.IO.FileMode * int * Nullable&lt;int64&gt; * int64 * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.DownloadToFileParallelAsync : string * System.IO.FileMode * int * Nullable&lt;int64&gt; * int64 * Nullable&lt;int64&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.DownloadToFileParallelAsync (path, mode, parallelIOCount, rangeSizeInBytes, offset, length, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="mode" Type="System.IO.FileMode" />
        <Parameter Name="parallelIOCount" Type="System.Int32" />
        <Parameter Name="rangeSizeInBytes" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="offset" Type="System.Int64" />
        <Parameter Name="length" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="path">Eine Zeichenfolge, die den Pfad zur Zieldatei enthält.</param>
        <param name="mode">Ein <see cref="T:System.IO.FileMode" /> -Enumerationswert ab, der bestimmt, wie die Datei geöffnet oder erstellt.</param>
        <param name="parallelIOCount">Die maximale Anzahl von Bereichen, die gleichzeitig heruntergeladen werden können</param>
        <param name="rangeSizeInBytes">Die Größe jedes einzelnen Bereichs in Bytes, die parallel gedownloadet wird.
            Die Bereichsgröße muss ein Vielfaches von 4 KB und mindestens 4 MB sein. MD5 ist aktiviert, wenn kein Wert den Standardwert 4 MB mindestens 16 MB bei transactional übergeben wird.</param>
        <param name="offset">Der Offset des BLOBs.</param>
        <param name="length">Die Anzahl der Bytes, die herunterladen.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang, um den Inhalt eines BLOBs in eine Datei herunterzuladen, durch parallele Anforderungen an.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
            Abhängig von der CPU, Arbeitsspeicher und Bandbreite sollte die ParallelIOCount und RangeSizeInBytes angepasst werden.
            Diese API sollte nur für größere Downloads, wie eine HEAD-Anforderung erfolgt vor dem Herunterladen von Daten verwendet werden.
            Verwenden Sie DownloadToFileAsync() für kleinere Blobs.
            Um die optimale Leistung zu erhalten, wird empfohlen, versuchen Sie es mehreren Werten und Durchsatz zu messen.
            Eine Position, an dem wäre die ParallelIOCount auf die Anzahl der CPUs festgelegt.
            Klicken Sie dann passen Sie die RangeSizeInBytes so an, dass ParallelIOCount Zeiten RangeSizeInBytes der Menge des Arbeitsspeichers an, dass den Prozess entspricht genutzt werden soll.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadToStream">
      <MemberSignature Language="C#" Value="public virtual void DownloadToStream (System.IO.Stream target, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DownloadToStream(class System.IO.Stream target, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.DownloadToStream(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DownloadToStream : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.DownloadToStream : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudBlob.DownloadToStream (target, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="target" Type="System.IO.Stream" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="target">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Zieldatenstrom darstellt.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt. Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Lädt den Inhalt eines BLOBs in einen Datenstrom herunter.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadToStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DownloadToStreamAsync (System.IO.Stream target);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DownloadToStreamAsync(class System.IO.Stream target) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.DownloadToStreamAsync(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function DownloadToStreamAsync (target As Stream) As Task" />
      <MemberSignature Language="F#" Value="abstract member DownloadToStreamAsync : System.IO.Stream -&gt; System.Threading.Tasks.Task&#xA;override this.DownloadToStreamAsync : System.IO.Stream -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.DownloadToStreamAsync target" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="target" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="target">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Zieldatenstrom darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Herunterladen der Inhalt eines BLOBs in einen Datenstrom.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadToStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DownloadToStreamAsync (System.IO.Stream target, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DownloadToStreamAsync(class System.IO.Stream target, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.DownloadToStreamAsync(System.IO.Stream,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DownloadToStreamAsync : System.IO.Stream * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.DownloadToStreamAsync : System.IO.Stream * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.DownloadToStreamAsync (target, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="target" Type="System.IO.Stream" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="target">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Zieldatenstrom darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Herunterladen der Inhalt eines BLOBs in einen Datenstrom.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadToStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DownloadToStreamAsync (System.IO.Stream target, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DownloadToStreamAsync(class System.IO.Stream target, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.DownloadToStreamAsync(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DownloadToStreamAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.DownloadToStreamAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.DownloadToStreamAsync (target, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="target" Type="System.IO.Stream" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="target">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Zieldatenstrom darstellt.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Herunterladen der Inhalt eines BLOBs in einen Datenstrom.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadToStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DownloadToStreamAsync (System.IO.Stream target, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DownloadToStreamAsync(class System.IO.Stream target, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.DownloadToStreamAsync(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DownloadToStreamAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.DownloadToStreamAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.DownloadToStreamAsync (target, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="target" Type="System.IO.Stream" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="target">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Zieldatenstrom darstellt.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Herunterladen der Inhalt eines BLOBs in einen Datenstrom.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DownloadToStreamAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DownloadToStreamAsync (System.IO.Stream target, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DownloadToStreamAsync(class System.IO.Stream target, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.IProgress`1&lt;class Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; progressHandler, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.DownloadToStreamAsync(System.IO.Stream,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.IProgress{Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DownloadToStreamAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.DownloadToStreamAsync : System.IO.Stream * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.DownloadToStreamAsync (target, accessCondition, options, operationContext, progressHandler, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="target" Type="System.IO.Stream" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="progressHandler" Type="System.IProgress&lt;Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="target">Ein <see cref="T:System.IO.Stream" /> Objekt, das den Zieldatenstrom darstellt.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="progressHandler"> Ein <see cref="T:System.IProgress`1" /> Objekt behandelt <see cref="T:Microsoft.WindowsAzure.Storage.Core.Util.StorageProgress" /> Nachrichten.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Herunterladen der Inhalt eines BLOBs in einen Datenstrom.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndAbortCopy">
      <MemberSignature Language="C#" Value="public virtual void EndAbortCopy (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndAbortCopy(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.EndAbortCopy(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndAbortCopy (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndAbortCopy : IAsyncResult -&gt; unit&#xA;override this.EndAbortCopy : IAsyncResult -&gt; unit" Usage="cloudBlob.EndAbortCopy asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</param>
        <summary>
            Beendet einen asynchronen Vorgang zum Abbrechen eines laufenden Blob-Kopiervorgangs.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndAcquireLease">
      <MemberSignature Language="C#" Value="public virtual string EndAcquireLease (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string EndAcquireLease(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.EndAcquireLease(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndAcquireLease (asyncResult As IAsyncResult) As String" />
      <MemberSignature Language="F#" Value="abstract member EndAcquireLease : IAsyncResult -&gt; string&#xA;override this.EndAcquireLease : IAsyncResult -&gt; string" Usage="cloudBlob.EndAcquireLease asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Ein "IAsyncResult", die auf den ausstehenden asynchronen Vorgang verweist.</param>
        <summary>
            Beendet einen asynchronen Vorgang zum Abrufen einer Lease für dieses Blob.
            </summary>
        <returns>Die ID der erworbenen Lease.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndBreakLease">
      <MemberSignature Language="C#" Value="public virtual TimeSpan EndBreakLease (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance valuetype System.TimeSpan EndBreakLease(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.EndBreakLease(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndBreakLease (asyncResult As IAsyncResult) As TimeSpan" />
      <MemberSignature Language="F#" Value="abstract member EndBreakLease : IAsyncResult -&gt; TimeSpan&#xA;override this.EndBreakLease : IAsyncResult -&gt; TimeSpan" Usage="cloudBlob.EndBreakLease asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Ein "IAsyncResult", die auf den ausstehenden asynchronen Vorgang verweist.</param>
        <summary>
            Beendet einen asynchronen Vorgang zum Unterbrechen der aktuellen Lease für dieses Blob.
            </summary>
        <returns>Ein <see cref="T:System.TimeSpan" /> , das die Zeitspanne, bevor die Lease, auf dem zweiten endet darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndChangeLease">
      <MemberSignature Language="C#" Value="public virtual string EndChangeLease (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string EndChangeLease(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.EndChangeLease(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndChangeLease (asyncResult As IAsyncResult) As String" />
      <MemberSignature Language="F#" Value="abstract member EndChangeLease : IAsyncResult -&gt; string&#xA;override this.EndChangeLease : IAsyncResult -&gt; string" Usage="cloudBlob.EndChangeLease asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</param>
        <summary>
            Beendet einen asynchronen Vorgang zum Ändern der Lease für dieses Blob.
            </summary>
        <returns>Die neue Lease-ID.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndDelete">
      <MemberSignature Language="C#" Value="public virtual void EndDelete (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndDelete(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.EndDelete(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndDelete (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndDelete : IAsyncResult -&gt; unit&#xA;override this.EndDelete : IAsyncResult -&gt; unit" Usage="cloudBlob.EndDelete asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</param>
        <summary>
            Beendet einen asynchronen Vorgang zum Löschen des BLOBs.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndDeleteIfExists">
      <MemberSignature Language="C#" Value="public virtual bool EndDeleteIfExists (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool EndDeleteIfExists(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.EndDeleteIfExists(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndDeleteIfExists (asyncResult As IAsyncResult) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member EndDeleteIfExists : IAsyncResult -&gt; bool&#xA;override this.EndDeleteIfExists : IAsyncResult -&gt; bool" Usage="cloudBlob.EndDeleteIfExists asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</param>
        <summary>
            Gibt das Ergebnis einer asynchronen Anforderung zum Löschen des BLOBs, wenn sie bereits vorhanden ist.
            </summary>
        <returns>
          <c>"true"</c> Wenn das Blob bereits vorhanden war und gelöscht; andernfalls wurde, <c>"false"</c>.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndDownloadRangeToByteArray">
      <MemberSignature Language="C#" Value="public virtual int EndDownloadRangeToByteArray (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 EndDownloadRangeToByteArray(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.EndDownloadRangeToByteArray(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndDownloadRangeToByteArray (asyncResult As IAsyncResult) As Integer" />
      <MemberSignature Language="F#" Value="abstract member EndDownloadRangeToByteArray : IAsyncResult -&gt; int&#xA;override this.EndDownloadRangeToByteArray : IAsyncResult -&gt; int" Usage="cloudBlob.EndDownloadRangeToByteArray asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</param>
        <summary>
            Beendet einen asynchronen Vorgang zum Herunterladen eines Bereichs von Bytes aus einem Blob in ein Bytearray.
            </summary>
        <returns>Die Gesamtanzahl der in den Puffer gelesenen Bytes.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndDownloadRangeToStream">
      <MemberSignature Language="C#" Value="public virtual void EndDownloadRangeToStream (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndDownloadRangeToStream(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.EndDownloadRangeToStream(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndDownloadRangeToStream (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndDownloadRangeToStream : IAsyncResult -&gt; unit&#xA;override this.EndDownloadRangeToStream : IAsyncResult -&gt; unit" Usage="cloudBlob.EndDownloadRangeToStream asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</param>
        <summary>
            Beendet einen asynchronen Vorgang zum Herunterladen eines Bereichs von Bytes aus einem Blob in einen Datenstrom.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndDownloadToByteArray">
      <MemberSignature Language="C#" Value="public virtual int EndDownloadToByteArray (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 EndDownloadToByteArray(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.EndDownloadToByteArray(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndDownloadToByteArray (asyncResult As IAsyncResult) As Integer" />
      <MemberSignature Language="F#" Value="abstract member EndDownloadToByteArray : IAsyncResult -&gt; int&#xA;override this.EndDownloadToByteArray : IAsyncResult -&gt; int" Usage="cloudBlob.EndDownloadToByteArray asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</param>
        <summary>
            Beendet einen asynchronen Vorgang, um den Inhalt eines BLOBs in ein Bytearray herunterzuladen.
            </summary>
        <returns>Die Gesamtanzahl der in den Puffer gelesenen Bytes.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndDownloadToFile">
      <MemberSignature Language="C#" Value="public virtual void EndDownloadToFile (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndDownloadToFile(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.EndDownloadToFile(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndDownloadToFile (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndDownloadToFile : IAsyncResult -&gt; unit&#xA;override this.EndDownloadToFile : IAsyncResult -&gt; unit" Usage="cloudBlob.EndDownloadToFile asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</param>
        <summary>
            Beendet einen asynchronen Vorgang, um den Inhalt eines BLOBs in eine Datei herunterladen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndDownloadToStream">
      <MemberSignature Language="C#" Value="public virtual void EndDownloadToStream (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndDownloadToStream(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.EndDownloadToStream(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndDownloadToStream (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndDownloadToStream : IAsyncResult -&gt; unit&#xA;override this.EndDownloadToStream : IAsyncResult -&gt; unit" Usage="cloudBlob.EndDownloadToStream asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</param>
        <summary>
            Beendet einen asynchronen Vorgang zum Herunterladen der Inhalt eines BLOBs in einen Datenstrom.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndExists">
      <MemberSignature Language="C#" Value="public virtual bool EndExists (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool EndExists(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.EndExists(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndExists (asyncResult As IAsyncResult) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member EndExists : IAsyncResult -&gt; bool&#xA;override this.EndExists : IAsyncResult -&gt; bool" Usage="cloudBlob.EndExists asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</param>
        <summary>
            Gibt das asynchrone Ergebnis der Anforderung an das Vorhandensein des BLOBs zu überprüfen.
            </summary>
        <returns>
          <c>"true"</c> , wenn das Blob vorhanden ist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndFetchAttributes">
      <MemberSignature Language="C#" Value="public virtual void EndFetchAttributes (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndFetchAttributes(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.EndFetchAttributes(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndFetchAttributes (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndFetchAttributes : IAsyncResult -&gt; unit&#xA;override this.EndFetchAttributes : IAsyncResult -&gt; unit" Usage="cloudBlob.EndFetchAttributes asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</param>
        <summary>
            Beendet einen asynchronen Vorgang zum Auffüllen von Eigenschaften und Metadaten des BLOBs.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndOpenRead">
      <MemberSignature Language="C#" Value="public virtual System.IO.Stream EndOpenRead (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.IO.Stream EndOpenRead(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.EndOpenRead(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndOpenRead (asyncResult As IAsyncResult) As Stream" />
      <MemberSignature Language="F#" Value="abstract member EndOpenRead : IAsyncResult -&gt; System.IO.Stream&#xA;override this.EndOpenRead : IAsyncResult -&gt; System.IO.Stream" Usage="cloudBlob.EndOpenRead asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</param>
        <summary>
            Beendet einen asynchronen Vorgang zum Öffnen von eines Datenstroms zum Lesen aus dem Blob.
            </summary>
        <returns>Ein <see cref="T:System.IO.Stream" /> Objekt, das zum Lesen aus dem Blob verwendet wird.</returns>
        <remarks>
          <para>Auf der <see cref="T:System.IO.Stream" /> von dieser Methode zurückgegebene Objekt der <see cref="M:System.IO.Stream.EndRead(System.IAsyncResult)" /> Methode muss genau einmal aufgerufen werden, für jede <see cref="M:System.IO.Stream.BeginRead(System.Byte[],System.Int32,System.Int32,System.AsyncCallback,System.Object)" /> aufrufen. Wegen eines Fehlers beim Beenden das Lesen Prozess stellen Sie vor Beginn einer anderen lesen verarbeiten kann zu unerwartetem Verhalten führen.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EndReleaseLease">
      <MemberSignature Language="C#" Value="public virtual void EndReleaseLease (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndReleaseLease(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.EndReleaseLease(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndReleaseLease (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndReleaseLease : IAsyncResult -&gt; unit&#xA;override this.EndReleaseLease : IAsyncResult -&gt; unit" Usage="cloudBlob.EndReleaseLease asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Ein "IAsyncResult", die auf den ausstehenden asynchronen Vorgang verweist.</param>
        <summary>
            Beendet einen asynchronen Vorgang zum Freigeben der Lease für dieses Blob.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndRenewLease">
      <MemberSignature Language="C#" Value="public virtual void EndRenewLease (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndRenewLease(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.EndRenewLease(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndRenewLease (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndRenewLease : IAsyncResult -&gt; unit&#xA;override this.EndRenewLease : IAsyncResult -&gt; unit" Usage="cloudBlob.EndRenewLease asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</param>
        <summary>
            Beendet einen asynchronen Vorgang zum Erneuern einer Lease für dieses Blob.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndRotateEncryptionKey">
      <MemberSignature Language="C#" Value="public virtual void EndRotateEncryptionKey (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndRotateEncryptionKey(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.EndRotateEncryptionKey(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndRotateEncryptionKey (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndRotateEncryptionKey : IAsyncResult -&gt; unit&#xA;override this.EndRotateEncryptionKey : IAsyncResult -&gt; unit" Usage="cloudBlob.EndRotateEncryptionKey asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</param>
        <summary>
            Beendet einen asynchronen Vorgang zum Drehen des Verschlüsselungsschlüssels für dieses Blob.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndSetMetadata">
      <MemberSignature Language="C#" Value="public virtual void EndSetMetadata (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndSetMetadata(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.EndSetMetadata(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndSetMetadata (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndSetMetadata : IAsyncResult -&gt; unit&#xA;override this.EndSetMetadata : IAsyncResult -&gt; unit" Usage="cloudBlob.EndSetMetadata asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</param>
        <summary>
            Beendet einen asynchronen Vorgang, um die Metadaten des BLOBs zu aktualisieren.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndSetProperties">
      <MemberSignature Language="C#" Value="public virtual void EndSetProperties (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndSetProperties(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.EndSetProperties(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndSetProperties (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndSetProperties : IAsyncResult -&gt; unit&#xA;override this.EndSetProperties : IAsyncResult -&gt; unit" Usage="cloudBlob.EndSetProperties asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</param>
        <summary>
            Beendet einen asynchronen Vorgang, um die Eigenschaften des BLOBs zu aktualisieren.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndSnapshot">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.CloudBlob EndSnapshot (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.CloudBlob EndSnapshot(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.EndSnapshot(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndSnapshot (asyncResult As IAsyncResult) As CloudBlob" />
      <MemberSignature Language="F#" Value="abstract member EndSnapshot : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlob&#xA;override this.EndSnapshot : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlob" Usage="cloudBlob.EndSnapshot asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CloudBlob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</param>
        <summary>
            Beendet einen asynchronen Vorgang zum Erstellen einer Momentaufnahme des BLOBs.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> -Objekt, das eine Blob-Momentaufnahme ist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndStartCopy">
      <MemberSignature Language="C#" Value="public virtual string EndStartCopy (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string EndStartCopy(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.EndStartCopy(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndStartCopy (asyncResult As IAsyncResult) As String" />
      <MemberSignature Language="F#" Value="abstract member EndStartCopy : IAsyncResult -&gt; string&#xA;override this.EndStartCopy : IAsyncResult -&gt; string" Usage="cloudBlob.EndStartCopy asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</param>
        <summary>
            Beendet einen asynchronen Vorgang zum Starten des Blob-Inhalte, Eigenschaften und Metadaten in dieses Blob kopiert.
            </summary>
        <returns>Eine Zeichenfolge, die den Kopiervorgang zugeordnete Kopie-ID enthält.</returns>
        <remarks>
            Diese Methode ruft die Blob-ETag, Uhrzeit der letzten Änderung und Teil den Kopierstatus ab.
            Die Kopie-ID und kopieren Sie den Statusfeldern abgerufen werden, und die restliche den Kopierstatus deaktiviert ist.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Exists">
      <MemberSignature Language="C#" Value="public virtual bool Exists (Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Exists(class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.Exists(Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Exists : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool&#xA;override this.Exists : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool" Usage="cloudBlob.Exists (options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt. Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Überprüft, ob das Blob vorhanden ist.
            </summary>
        <returns>
          <c>"true"</c> , wenn das Blob vorhanden ist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.ExistsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ExistsAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member ExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.ExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudBlob.ExistsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Initiiert einen asynchronen Vorgang zum Vorhandensein des BLOBs zu überprüfen.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.ExistsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.ExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudBlob.ExistsAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Vorhandensein des BLOBs zu überprüfen.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.ExistsAsync(Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExistsAsync : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.ExistsAsync : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudBlob.ExistsAsync (options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Vorhandensein des BLOBs zu überprüfen.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.ExistsAsync(Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExistsAsync : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.ExistsAsync : Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudBlob.ExistsAsync (options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Vorhandensein des BLOBs zu überprüfen.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FetchAttributes">
      <MemberSignature Language="C#" Value="public virtual void FetchAttributes (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void FetchAttributes(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member FetchAttributes : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.FetchAttributes : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudBlob.FetchAttributes (accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt. Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Füllt Eigenschaften und Metadaten eines BLOBs.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FetchAttributesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task FetchAttributesAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task FetchAttributesAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function FetchAttributesAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member FetchAttributesAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.FetchAttributesAsync : unit -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.FetchAttributesAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Initiiert einen asynchronen Vorgang zum Auffüllen von Eigenschaften und Metadaten des BLOBs.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FetchAttributesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task FetchAttributesAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task FetchAttributesAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member FetchAttributesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.FetchAttributesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.FetchAttributesAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Auffüllen von Eigenschaften und Metadaten des BLOBs.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FetchAttributesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task FetchAttributesAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task FetchAttributesAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member FetchAttributesAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.FetchAttributesAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.FetchAttributesAsync (accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Auffüllen von Eigenschaften und Metadaten des BLOBs.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FetchAttributesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task FetchAttributesAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task FetchAttributesAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member FetchAttributesAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.FetchAttributesAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.FetchAttributesAsync (accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Auffüllen von Eigenschaften und Metadaten des BLOBs.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSharedAccessSignature">
      <MemberSignature Language="C#" Value="public string GetSharedAccessSignature (Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy policy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string GetSharedAccessSignature(class Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy policy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.GetSharedAccessSignature(Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSharedAccessSignature (policy As SharedAccessBlobPolicy) As String" />
      <MemberSignature Language="F#" Value="abstract member GetSharedAccessSignature : Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy -&gt; string&#xA;override this.GetSharedAccessSignature : Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy -&gt; string" Usage="cloudBlob.GetSharedAccessSignature policy" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="policy" Type="Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" />
      </Parameters>
      <Docs>
        <param name="policy">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" /> Objekt, das die Zugriffsrichtlinie für die SAS angibt.</param>
        <summary>
            Gibt eine SAS für das Blob zurück.
            </summary>
        <returns>Eine SAS als URI-Abfragezeichenfolge.</returns>
        <remarks>Die zurückgegebene Abfragezeichenfolge enthält das vorangestellte Fragezeichen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSharedAccessSignature">
      <MemberSignature Language="C#" Value="public string GetSharedAccessSignature (Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy policy, Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders headers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string GetSharedAccessSignature(class Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy policy, class Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders headers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.GetSharedAccessSignature(Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy,Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSharedAccessSignature (policy As SharedAccessBlobPolicy, headers As SharedAccessBlobHeaders) As String" />
      <MemberSignature Language="F#" Value="abstract member GetSharedAccessSignature : Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy * Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders -&gt; string&#xA;override this.GetSharedAccessSignature : Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy * Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders -&gt; string" Usage="cloudBlob.GetSharedAccessSignature (policy, headers)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="policy" Type="Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" />
        <Parameter Name="headers" Type="Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders" />
      </Parameters>
      <Docs>
        <param name="policy">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" /> Objekt, das die Zugriffsrichtlinie für die SAS angibt.</param>
        <param name="headers">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders" /> -Objekt, mit optionalen Headerwerte, legen Sie für ein Blob mit dieser SAS zugegriffen.</param>
        <summary>
            Gibt eine SAS für das Blob zurück.
            </summary>
        <returns>Eine SAS als URI-Abfragezeichenfolge.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSharedAccessSignature">
      <MemberSignature Language="C#" Value="public string GetSharedAccessSignature (Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy policy, string groupPolicyIdentifier);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string GetSharedAccessSignature(class Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy policy, string groupPolicyIdentifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.GetSharedAccessSignature(Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSharedAccessSignature (policy As SharedAccessBlobPolicy, groupPolicyIdentifier As String) As String" />
      <MemberSignature Language="F#" Value="abstract member GetSharedAccessSignature : Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy * string -&gt; string&#xA;override this.GetSharedAccessSignature : Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy * string -&gt; string" Usage="cloudBlob.GetSharedAccessSignature (policy, groupPolicyIdentifier)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="policy" Type="Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" />
        <Parameter Name="groupPolicyIdentifier" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="policy">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" /> Objekt, das die Zugriffsrichtlinie für die SAS angibt.</param>
        <param name="groupPolicyIdentifier">Eine Zeichenfolge, die eine gespeicherte Zugriffsrichtlinie identifiziert.</param>
        <summary>
            Gibt eine SAS für das Blob zurück.
            </summary>
        <returns>Eine SAS als URI-Abfragezeichenfolge.</returns>
        <remarks>Die zurückgegebene Abfragezeichenfolge enthält das vorangestellte Fragezeichen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSharedAccessSignature">
      <MemberSignature Language="C#" Value="public string GetSharedAccessSignature (Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy policy, Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders headers, string groupPolicyIdentifier);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string GetSharedAccessSignature(class Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy policy, class Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders headers, string groupPolicyIdentifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.GetSharedAccessSignature(Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy,Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSharedAccessSignature (policy As SharedAccessBlobPolicy, headers As SharedAccessBlobHeaders, groupPolicyIdentifier As String) As String" />
      <MemberSignature Language="F#" Value="abstract member GetSharedAccessSignature : Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy * Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders * string -&gt; string&#xA;override this.GetSharedAccessSignature : Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy * Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders * string -&gt; string" Usage="cloudBlob.GetSharedAccessSignature (policy, headers, groupPolicyIdentifier)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="policy" Type="Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" />
        <Parameter Name="headers" Type="Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders" />
        <Parameter Name="groupPolicyIdentifier" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="policy">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" /> Objekt, das die Zugriffsrichtlinie für die SAS angibt.</param>
        <param name="headers">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders" /> -Objekt, mit optionalen Headerwerte, legen Sie für ein Blob mit dieser SAS zugegriffen.</param>
        <param name="groupPolicyIdentifier">Eine Zeichenfolge, die eine gespeicherte Zugriffsrichtlinie identifiziert.</param>
        <summary>
            Gibt eine SAS für das Blob zurück.
            </summary>
        <returns>Eine SAS als URI-Abfragezeichenfolge.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSharedAccessSignature">
      <MemberSignature Language="C#" Value="public string GetSharedAccessSignature (Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy policy, Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders headers, string groupPolicyIdentifier, Nullable&lt;Microsoft.WindowsAzure.Storage.SharedAccessProtocol&gt; protocols, Microsoft.WindowsAzure.Storage.IPAddressOrRange ipAddressOrRange);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string GetSharedAccessSignature(class Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy policy, class Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders headers, string groupPolicyIdentifier, valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.SharedAccessProtocol&gt; protocols, class Microsoft.WindowsAzure.Storage.IPAddressOrRange ipAddressOrRange) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.GetSharedAccessSignature(Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy,Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders,System.String,System.Nullable{Microsoft.WindowsAzure.Storage.SharedAccessProtocol},Microsoft.WindowsAzure.Storage.IPAddressOrRange)" />
      <MemberSignature Language="F#" Value="abstract member GetSharedAccessSignature : Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy * Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders * string * Nullable&lt;Microsoft.WindowsAzure.Storage.SharedAccessProtocol&gt; * Microsoft.WindowsAzure.Storage.IPAddressOrRange -&gt; string&#xA;override this.GetSharedAccessSignature : Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy * Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders * string * Nullable&lt;Microsoft.WindowsAzure.Storage.SharedAccessProtocol&gt; * Microsoft.WindowsAzure.Storage.IPAddressOrRange -&gt; string" Usage="cloudBlob.GetSharedAccessSignature (policy, headers, groupPolicyIdentifier, protocols, ipAddressOrRange)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="policy" Type="Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" />
        <Parameter Name="headers" Type="Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders" />
        <Parameter Name="groupPolicyIdentifier" Type="System.String" />
        <Parameter Name="protocols" Type="System.Nullable&lt;Microsoft.WindowsAzure.Storage.SharedAccessProtocol&gt;" />
        <Parameter Name="ipAddressOrRange" Type="Microsoft.WindowsAzure.Storage.IPAddressOrRange" />
      </Parameters>
      <Docs>
        <param name="policy">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobPolicy" /> Objekt, das die Zugriffsrichtlinie für die SAS angibt.</param>
        <param name="headers">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.SharedAccessBlobHeaders" /> -Objekt, mit optionalen Headerwerte, legen Sie für ein Blob mit dieser SAS zugegriffen.</param>
        <param name="groupPolicyIdentifier">Eine Zeichenfolge, die eine gespeicherte Zugriffsrichtlinie identifiziert.</param>
        <param name="protocols">Die zulässige Protokolle (nur Https oder http und Https). NULL, wenn Sie nicht Protokoll beschränken möchten.</param>
        <param name="ipAddressOrRange">Die zulässigen IP-Adresse oder IP-Adressbereich. NULL, wenn Sie einschränken möchten, nicht basierend auf IP-Adresse.</param>
        <summary>
            Gibt eine SAS für das Blob zurück.
            </summary>
        <returns>Eine SAS als URI-Abfragezeichenfolge.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSnapshot">
      <MemberSignature Language="C#" Value="public bool IsSnapshot { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsSnapshot" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.IsSnapshot" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsSnapshot As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsSnapshot : bool" Usage="Microsoft.WindowsAzure.Storage.Blob.CloudBlob.IsSnapshot" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Wert, der angibt, ob dieses Blob eine Momentaufnahme ist.
            </summary>
        <value>
          <c>"true"</c> Wenn dieses Blob eine Momentaufnahme ist; andernfalls <c>"false"</c>.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Metadata { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Metadata As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.CloudBlob.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die benutzerdefinierten Metadaten für das Blob ab.
            </summary>
        <value>Ein <see cref="T:System.Collections.Generic.IDictionary`2" /> Objekt, das die Metadaten des BLOBs als Auflistung von Name-Wert-Paare enthält.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.WindowsAzure.Storage.Blob.CloudBlob.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Namen des BLOBs ab.
            </summary>
        <value>Eine Zeichenfolge, die den Namen des BLOBs enthält.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenRead">
      <MemberSignature Language="C#" Value="public virtual System.IO.Stream OpenRead (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.IO.Stream OpenRead(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.OpenRead(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member OpenRead : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.IO.Stream&#xA;override this.OpenRead : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.IO.Stream" Usage="cloudBlob.OpenRead (accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt. Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Öffnet einen Stream zum Lesen aus dem Blob.
            </summary>
        <returns>Ein <see cref="T:System.IO.Stream" /> Objekt, das zum Lesen aus dem Blob verwendet wird.</returns>
        <remarks>
          <para>Beachten Sie, dass diese Methode immer einen Aufruf an sendet die <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributes(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" /> Methode im Hintergrund.</para>
          <para>Legen Sie die <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.StreamMinimumReadSizeInBytes" /> Eigenschaft vor dem Aufrufen dieser Methode zum Angeben der Mindestanzahl von Bytes, die beim Lesen aus dem Datenstrom gepuffert werden sollen. Der Wert muss mindestens 16 KB sein.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenReadAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.IO.Stream&gt; OpenReadAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.IO.Stream&gt; OpenReadAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.OpenReadAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function OpenReadAsync () As Task(Of Stream)" />
      <MemberSignature Language="F#" Value="abstract member OpenReadAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.IO.Stream&gt;&#xA;override this.OpenReadAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.IO.Stream&gt;" Usage="cloudBlob.OpenReadAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.IO.Stream&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Initiiert einen asynchronen Vorgang zum Öffnen von eines Datenstroms zum Lesen aus dem Blob.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:System.IO.Stream" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <para>Auf der <see cref="T:System.IO.Stream" /> von dieser Methode zurückgegebene Objekt der <see cref="M:System.IO.Stream.EndRead(System.IAsyncResult)" /> Methode muss genau einmal aufgerufen werden, für jede <see cref="M:System.IO.Stream.BeginRead(System.Byte[],System.Int32,System.Int32,System.AsyncCallback,System.Object)" /> aufrufen. Wegen eines Fehlers beim Beenden das Lesen Prozess stellen Sie vor Beginn einer anderen lesen verarbeiten kann zu unerwartetem Verhalten führen.</para>
          <para>Beachten Sie, dass diese Methode immer einen Aufruf an sendet die <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" /> Methode im Hintergrund.</para>
          <para>Legen Sie die <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.StreamMinimumReadSizeInBytes" /> Eigenschaft vor dem Aufrufen dieser Methode zum Angeben der Mindestanzahl von Bytes, die beim Lesen aus dem Datenstrom gepuffert werden sollen. Der Wert muss mindestens 16 KB sein.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenReadAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.IO.Stream&gt; OpenReadAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.IO.Stream&gt; OpenReadAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.OpenReadAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OpenReadAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.IO.Stream&gt;&#xA;override this.OpenReadAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.IO.Stream&gt;" Usage="cloudBlob.OpenReadAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.IO.Stream&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Öffnen von eines Datenstroms zum Lesen aus dem Blob.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:System.IO.Stream" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <para>Auf der <see cref="T:System.IO.Stream" /> von dieser Methode zurückgegebene Objekt der <see cref="M:System.IO.Stream.EndRead(System.IAsyncResult)" /> Methode muss genau einmal aufgerufen werden, für jede <see cref="M:System.IO.Stream.BeginRead(System.Byte[],System.Int32,System.Int32,System.AsyncCallback,System.Object)" /> aufrufen. Wegen eines Fehlers beim Beenden das Lesen Prozess stellen Sie vor Beginn einer anderen lesen verarbeiten kann zu unerwartetem Verhalten führen.</para>
          <para>Beachten Sie, dass diese Methode immer einen Aufruf an sendet die <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" /> Methode im Hintergrund.</para>
          <para>Legen Sie die <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.StreamMinimumReadSizeInBytes" /> Eigenschaft vor dem Aufrufen dieser Methode zum Angeben der Mindestanzahl von Bytes, die beim Lesen aus dem Datenstrom gepuffert werden sollen. Der Wert muss mindestens 16 KB sein.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenReadAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.IO.Stream&gt; OpenReadAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.IO.Stream&gt; OpenReadAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.OpenReadAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member OpenReadAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;System.IO.Stream&gt;&#xA;override this.OpenReadAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;System.IO.Stream&gt;" Usage="cloudBlob.OpenReadAsync (accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.IO.Stream&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Öffnen von eines Datenstroms zum Lesen aus dem Blob.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:System.IO.Stream" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <para>Auf der <see cref="T:System.IO.Stream" /> von dieser Methode zurückgegebene Objekt der <see cref="M:System.IO.Stream.EndRead(System.IAsyncResult)" /> Methode muss genau einmal aufgerufen werden, für jede <see cref="M:System.IO.Stream.BeginRead(System.Byte[],System.Int32,System.Int32,System.AsyncCallback,System.Object)" /> aufrufen. Wegen eines Fehlers beim Beenden das Lesen Prozess stellen Sie vor Beginn einer anderen lesen verarbeiten kann zu unerwartetem Verhalten führen.</para>
          <para>Beachten Sie, dass diese Methode immer einen Aufruf an sendet die <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" /> Methode im Hintergrund.</para>
          <para>Legen Sie die <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.StreamMinimumReadSizeInBytes" /> Eigenschaft vor dem Aufrufen dieser Methode zum Angeben der Mindestanzahl von Bytes, die beim Lesen aus dem Datenstrom gepuffert werden sollen. Der Wert muss mindestens 16 KB sein.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenReadAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.IO.Stream&gt; OpenReadAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.IO.Stream&gt; OpenReadAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.OpenReadAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OpenReadAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.IO.Stream&gt;&#xA;override this.OpenReadAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.IO.Stream&gt;" Usage="cloudBlob.OpenReadAsync (accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.IO.Stream&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Öffnen von eines Datenstroms zum Lesen aus dem Blob.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:System.IO.Stream" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>
          <para>Auf der <see cref="T:System.IO.Stream" /> von dieser Methode zurückgegebene Objekt der <see cref="M:System.IO.Stream.EndRead(System.IAsyncResult)" /> Methode muss genau einmal aufgerufen werden, für jede <see cref="M:System.IO.Stream.BeginRead(System.Byte[],System.Int32,System.Int32,System.AsyncCallback,System.Object)" /> aufrufen. Wegen eines Fehlers beim Beenden das Lesen Prozess stellen Sie vor Beginn einer anderen lesen verarbeiten kann zu unerwartetem Verhalten führen.</para>
          <para>Beachten Sie, dass diese Methode immer einen Aufruf an sendet die <see cref="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.FetchAttributesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" /> Methode im Hintergrund.</para>
          <para>Legen Sie die <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.StreamMinimumReadSizeInBytes" /> Eigenschaft vor dem Aufrufen dieser Methode zum Angeben der Mindestanzahl von Bytes, die beim Lesen aus dem Datenstrom gepuffert werden sollen. Der Wert muss mindestens 16 KB sein.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Parent">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory Parent { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory Parent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.Parent" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Parent As CloudBlobDirectory" />
      <MemberSignature Language="F#" Value="member this.Parent : Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" Usage="Microsoft.WindowsAzure.Storage.Blob.CloudBlob.Parent" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.Blob.IListBlobItem.Parent</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" /> Objekt, das das virtuelle übergeordnete Verzeichnis für das Blob darstellt.
            </summary>
        <value>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobDirectory" />-Objekt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.BlobProperties Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Blob.BlobProperties Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As BlobProperties" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.WindowsAzure.Storage.Blob.BlobProperties" Usage="Microsoft.WindowsAzure.Storage.Blob.CloudBlob.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlobProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Systemeigenschaften des BLOBs ab.
            </summary>
        <value>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobProperties" />-Objekt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReleaseLease">
      <MemberSignature Language="C#" Value="public virtual void ReleaseLease (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReleaseLease(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.ReleaseLease(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ReleaseLease : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.ReleaseLease : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudBlob.ReleaseLease (accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung, die erfüllt sein muss, damit die Anforderung zu fortfahren, darstellt, einschließlich einer erforderlichen Lease-ID.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt. Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Gibt die Lease für dieses Blob frei.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReleaseLeaseAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task ReleaseLeaseAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ReleaseLeaseAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.ReleaseLeaseAsync(Microsoft.WindowsAzure.Storage.AccessCondition)" />
      <MemberSignature Language="F#" Value="abstract member ReleaseLeaseAsync : Microsoft.WindowsAzure.Storage.AccessCondition -&gt; System.Threading.Tasks.Task&#xA;override this.ReleaseLeaseAsync : Microsoft.WindowsAzure.Storage.AccessCondition -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.ReleaseLeaseAsync accessCondition" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
      </Parameters>
      <Docs>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung, die erfüllt sein muss, damit die Anforderung zu fortfahren, darstellt, einschließlich einer erforderlichen Lease-ID.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Freigeben der Lease für dieses Blob.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReleaseLeaseAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task ReleaseLeaseAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ReleaseLeaseAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.ReleaseLeaseAsync(Microsoft.WindowsAzure.Storage.AccessCondition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ReleaseLeaseAsync : Microsoft.WindowsAzure.Storage.AccessCondition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.ReleaseLeaseAsync : Microsoft.WindowsAzure.Storage.AccessCondition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.ReleaseLeaseAsync (accessCondition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung, die erfüllt sein muss, damit die Anforderung zu fortfahren, darstellt, einschließlich einer erforderlichen Lease-ID.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Freigeben der Lease für dieses Blob.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReleaseLeaseAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task ReleaseLeaseAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ReleaseLeaseAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.ReleaseLeaseAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ReleaseLeaseAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.ReleaseLeaseAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.ReleaseLeaseAsync (accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung, die erfüllt sein muss, damit die Anforderung zu fortfahren, darstellt, einschließlich einer erforderlichen Lease-ID.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Freigeben der Lease für dieses Blob.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReleaseLeaseAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task ReleaseLeaseAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ReleaseLeaseAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.ReleaseLeaseAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ReleaseLeaseAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.ReleaseLeaseAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.ReleaseLeaseAsync (accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung, die erfüllt sein muss, damit die Anforderung zu fortfahren, darstellt, einschließlich einer erforderlichen Lease-ID.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Freigeben der Lease für dieses Blob.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewLease">
      <MemberSignature Language="C#" Value="public virtual void RenewLease (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RenewLease(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.RenewLease(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member RenewLease : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.RenewLease : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudBlob.RenewLease (accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung, die erfüllt sein muss, damit die Anforderung zu fortfahren, darstellt, einschließlich einer erforderlichen Lease-ID.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.  Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erneuert eine Lease für dieses Blob.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewLeaseAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task RenewLeaseAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RenewLeaseAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.RenewLeaseAsync(Microsoft.WindowsAzure.Storage.AccessCondition)" />
      <MemberSignature Language="F#" Value="abstract member RenewLeaseAsync : Microsoft.WindowsAzure.Storage.AccessCondition -&gt; System.Threading.Tasks.Task&#xA;override this.RenewLeaseAsync : Microsoft.WindowsAzure.Storage.AccessCondition -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.RenewLeaseAsync accessCondition" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
      </Parameters>
      <Docs>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung, die erfüllt sein muss, damit die Anforderung zu fortfahren, darstellt, einschließlich einer erforderlichen Lease-ID.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Erneuern einer Lease für dieses Blob.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewLeaseAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task RenewLeaseAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RenewLeaseAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.RenewLeaseAsync(Microsoft.WindowsAzure.Storage.AccessCondition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RenewLeaseAsync : Microsoft.WindowsAzure.Storage.AccessCondition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.RenewLeaseAsync : Microsoft.WindowsAzure.Storage.AccessCondition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.RenewLeaseAsync (accessCondition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung, die erfüllt sein muss, damit die Anforderung zu fortfahren, darstellt, einschließlich einer erforderlichen Lease-ID.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Erneuern einer Lease für dieses Blob.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewLeaseAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task RenewLeaseAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RenewLeaseAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.RenewLeaseAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member RenewLeaseAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.RenewLeaseAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.RenewLeaseAsync (accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung, die erfüllt sein muss, damit die Anforderung zu fortfahren, darstellt, einschließlich einer erforderlichen Lease-ID.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Erneuern einer Lease für dieses Blob.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewLeaseAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task RenewLeaseAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RenewLeaseAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.RenewLeaseAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RenewLeaseAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.RenewLeaseAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.RenewLeaseAsync (accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> Objekt, das die Bedingung, die erfüllt sein muss, damit die Anforderung zu fortfahren, darstellt, einschließlich einer erforderlichen Lease-ID.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Erneuern einer Lease für dieses Blob.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RotateEncryptionKey">
      <MemberSignature Language="C#" Value="public virtual void RotateEncryptionKey (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RotateEncryptionKey(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.RotateEncryptionKey(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member RotateEncryptionKey : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.RotateEncryptionKey : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudBlob.RotateEncryptionKey (accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Für diesen Vorgang, es muss ein <see cref="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfMatchETag" />, <see cref="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfNoneMatchETag" />, <see cref="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfModifiedSinceTime" />, oder <see cref="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfNotModifiedSinceTime" /> Bedingung.  
            Ein <see cref="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfMatchETag" /> intern Bedingung hinzugefügt werden.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Dreht den Verschlüsselungsschlüssel für dieses Blob.
            Diese Methode wird nur der Schlüsselaustauschschlüssel nicht der CEK gedreht.  Weitere Informationen finden Sie auf https://azure.microsoft.com/en-us/documentation/articles/storage-client-side-encryption/
            </summary>
        <remarks>
            Diese Methode hat eine Reihe von Voraussetzungen:
            1. Das Blob muss verschlüsselt sein, für den Dienst mithilfe des Client-seitige ver-(nicht aufseiten des Dienstes Verschlüsselung).
            2. Das lokale Objekt muss die neueste Attribute aus dem Blob für den Dienst verfügen.  Dies kann durch Aufrufen von FetchAttributes() für das Blob oder durch Auflisten der Blobs im Container mit Metadaten erfolgen.
            3. Die Verschlüsselungsrichtlinie auf dem standardmäßigen BlobRequestOptions muss ein IKeyResolver kann zum Auflösen von alten Verschlüsselungsschlüssel enthalten.
            4. Die Verschlüsselungsrichtlinie auf dem standardmäßigen BlobRequestOptions muss ein IKey mit dem neuen Verschlüsselungsschlüssel enthalten.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RotateEncryptionKeyAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task RotateEncryptionKeyAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RotateEncryptionKeyAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.RotateEncryptionKeyAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function RotateEncryptionKeyAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member RotateEncryptionKeyAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.RotateEncryptionKeyAsync : unit -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.RotateEncryptionKeyAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Initiiert einen asynchronen Vorgang zum Drehen des Verschlüsselungsschlüssels für dieses Blob.
            Diese Methode wird nur der Schlüsselaustauschschlüssel nicht der CEK gedreht.  Weitere Informationen finden Sie auf https://azure.microsoft.com/en-us/documentation/articles/storage-client-side-encryption/
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
            Diese Methode hat eine Reihe von Voraussetzungen:
            1. Das Blob muss verschlüsselt sein, für den Dienst mithilfe des Client-seitige ver-(nicht aufseiten des Dienstes Verschlüsselung).
            2. Das lokale Objekt muss die neueste Attribute aus dem Blob für den Dienst verfügen.  Dies kann durch Aufrufen von FetchAttributes() für das Blob oder durch Auflisten der Blobs im Container mit Metadaten erfolgen.
            3. Die Verschlüsselungsrichtlinie auf dem standardmäßigen BlobRequestOptions muss ein IKeyResolver kann zum Auflösen von alten Verschlüsselungsschlüssel enthalten.
            4. Die Verschlüsselungsrichtlinie auf dem standardmäßigen BlobRequestOptions muss ein IKey mit dem neuen Verschlüsselungsschlüssel enthalten.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RotateEncryptionKeyAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task RotateEncryptionKeyAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RotateEncryptionKeyAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.RotateEncryptionKeyAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RotateEncryptionKeyAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.RotateEncryptionKeyAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.RotateEncryptionKeyAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Drehen des Verschlüsselungsschlüssels für dieses Blob.
            Diese Methode wird nur der Schlüsselaustauschschlüssel nicht der CEK gedreht.  Weitere Informationen finden Sie auf https://azure.microsoft.com/en-us/documentation/articles/storage-client-side-encryption/
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
            Diese Methode hat eine Reihe von Voraussetzungen:
            1. Das Blob muss verschlüsselt sein, für den Dienst mithilfe des Client-seitige ver-(nicht aufseiten des Dienstes Verschlüsselung).
            2. Das lokale Objekt muss die neueste Attribute aus dem Blob für den Dienst verfügen.  Dies kann durch Aufrufen von FetchAttributes() für das Blob oder durch Auflisten der Blobs im Container mit Metadaten erfolgen.
            3. Die Verschlüsselungsrichtlinie auf dem standardmäßigen BlobRequestOptions muss ein IKeyResolver kann zum Auflösen von alten Verschlüsselungsschlüssel enthalten.
            4. Die Verschlüsselungsrichtlinie auf dem standardmäßigen BlobRequestOptions muss ein IKey mit dem neuen Verschlüsselungsschlüssel enthalten.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RotateEncryptionKeyAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task RotateEncryptionKeyAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RotateEncryptionKeyAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.RotateEncryptionKeyAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member RotateEncryptionKeyAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.RotateEncryptionKeyAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.RotateEncryptionKeyAsync (accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Für diesen Vorgang, es muss ein <see cref="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfMatchETag" />, <see cref="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfNoneMatchETag" />, <see cref="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfModifiedSinceTime" />, oder <see cref="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfNotModifiedSinceTime" /> Bedingung.  
            Ein <see cref="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfMatchETag" /> intern Bedingung hinzugefügt werden.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Drehen des Verschlüsselungsschlüssels für dieses Blob.
            Diese Methode wird nur der Schlüsselaustauschschlüssel nicht der CEK gedreht.  Weitere Informationen finden Sie auf https://azure.microsoft.com/en-us/documentation/articles/storage-client-side-encryption/
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
            Diese Methode hat eine Reihe von Voraussetzungen:
            1. Das Blob muss verschlüsselt sein, für den Dienst mithilfe des Client-seitige ver-(nicht aufseiten des Dienstes Verschlüsselung).
            2. Das lokale Objekt muss die neueste Attribute aus dem Blob für den Dienst verfügen.  Dies kann durch Aufrufen von FetchAttributes() für das Blob oder durch Auflisten der Blobs im Container mit Metadaten erfolgen.
            3. Die Verschlüsselungsrichtlinie auf dem standardmäßigen BlobRequestOptions muss ein IKeyResolver kann zum Auflösen von alten Verschlüsselungsschlüssel enthalten.
            4. Die Verschlüsselungsrichtlinie auf dem standardmäßigen BlobRequestOptions muss ein IKey mit dem neuen Verschlüsselungsschlüssel enthalten.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RotateEncryptionKeyAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task RotateEncryptionKeyAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RotateEncryptionKeyAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.RotateEncryptionKeyAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RotateEncryptionKeyAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.RotateEncryptionKeyAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.RotateEncryptionKeyAsync (accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Diagnostics.DebuggerStepThrough</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.WindowsAzure.Storage.Blob.CloudBlob/&lt;RotateEncryptionKeyAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Für diesen Vorgang, es muss ein <see cref="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfMatchETag" />, <see cref="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfNoneMatchETag" />, <see cref="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfModifiedSinceTime" />, oder <see cref="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfNotModifiedSinceTime" /> Bedingung.  
            Ein <see cref="P:Microsoft.WindowsAzure.Storage.AccessCondition.IfMatchETag" /> intern Bedingung hinzugefügt werden.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Drehen des Verschlüsselungsschlüssels für dieses Blob.
            Diese Methode wird nur der Schlüsselaustauschschlüssel nicht der CEK gedreht.  Weitere Informationen finden Sie auf https://azure.microsoft.com/en-us/documentation/articles/storage-client-side-encryption/
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>
            Diese Methode hat eine Reihe von Voraussetzungen:
            1. Das Blob muss verschlüsselt sein, für den Dienst mithilfe des Client-seitige ver-(nicht aufseiten des Dienstes Verschlüsselung).
            2. Das lokale Objekt muss die neueste Attribute aus dem Blob für den Dienst verfügen.  Dies kann durch Aufrufen von FetchAttributes() für das Blob oder durch Auflisten der Blobs im Container mit Metadaten erfolgen.
            3. Die Verschlüsselungsrichtlinie auf dem standardmäßigen BlobRequestOptions muss ein IKeyResolver kann zum Auflösen von alten Verschlüsselungsschlüssel enthalten.
            4. Die Verschlüsselungsrichtlinie auf dem standardmäßigen BlobRequestOptions muss ein IKey mit dem neuen Verschlüsselungsschlüssel enthalten.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceClient">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient ServiceClient { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient ServiceClient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.ServiceClient" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceClient As CloudBlobClient" />
      <MemberSignature Language="F#" Value="member this.ServiceClient : Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient" Usage="Microsoft.WindowsAzure.Storage.Blob.CloudBlob.ServiceClient" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient" /> Objekt, das den Blob-Dienst darstellt.
            </summary>
        <value>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobClient" />-Objekt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadata">
      <MemberSignature Language="C#" Value="public virtual void SetMetadata (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SetMetadata(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.SetMetadata(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetMetadata : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.SetMetadata : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudBlob.SetMetadata (accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt. Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Aktualisiert die Metadaten des BLOBs.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadataAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetMetadataAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetMetadataAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.SetMetadataAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function SetMetadataAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member SetMetadataAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.SetMetadataAsync : unit -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.SetMetadataAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Initiiert einen asynchronen Vorgang, um die Metadaten des BLOBs zu aktualisieren.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadataAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetMetadataAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetMetadataAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.SetMetadataAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetMetadataAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetMetadataAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.SetMetadataAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang, um die Metadaten des BLOBs zu aktualisieren.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadataAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetMetadataAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetMetadataAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.SetMetadataAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetMetadataAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.SetMetadataAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.SetMetadataAsync (accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang, um die Metadaten des BLOBs zu aktualisieren.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetMetadataAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetMetadataAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetMetadataAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.SetMetadataAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetMetadataAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetMetadataAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.SetMetadataAsync (accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang, um die Metadaten des BLOBs zu aktualisieren.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetProperties">
      <MemberSignature Language="C#" Value="public virtual void SetProperties (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SetProperties(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.SetProperties(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetProperties : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.SetProperties : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudBlob.SetProperties (accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt. Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Aktualisiert die Eigenschaften des BLOBs.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPropertiesAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPropertiesAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.SetPropertiesAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function SetPropertiesAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member SetPropertiesAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.SetPropertiesAsync : unit -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.SetPropertiesAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Initiiert einen asynchronen Vorgang, um die Eigenschaften des BLOBs zu aktualisieren.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPropertiesAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPropertiesAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.SetPropertiesAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetPropertiesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetPropertiesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.SetPropertiesAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang, um die Eigenschaften des BLOBs zu aktualisieren.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPropertiesAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPropertiesAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.SetPropertiesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetPropertiesAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.SetPropertiesAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.SetPropertiesAsync (accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang, um die Eigenschaften des BLOBs zu aktualisieren.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPropertiesAsync (Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPropertiesAsync(class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.SetPropertiesAsync(Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetPropertiesAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetPropertiesAsync : Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudBlob.SetPropertiesAsync (accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang, um die Eigenschaften des BLOBs zu aktualisieren.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Snapshot">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Blob.CloudBlob Snapshot (System.Collections.Generic.IDictionary&lt;string,string&gt; metadata = null, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Blob.CloudBlob Snapshot(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; metadata, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.Snapshot(System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Snapshot : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlob&#xA;override this.Snapshot : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Blob.CloudBlob" Usage="cloudBlob.Snapshot (metadata, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CloudBlob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="metadata" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="metadata">Eine Auflistung von Name-Wert-Paare definieren die Metadaten der Momentaufnahme.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt oder <c>null</c>. Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellt eine Momentaufnahme des BLOBs.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> -Objekt, das eine Blob-Momentaufnahme ist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SnapshotAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlob&gt; SnapshotAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.CloudBlob&gt; SnapshotAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.SnapshotAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function SnapshotAsync () As Task(Of CloudBlob)" />
      <MemberSignature Language="F#" Value="abstract member SnapshotAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlob&gt;&#xA;override this.SnapshotAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlob&gt;" Usage="cloudBlob.SnapshotAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Initiiert einen asynchronen Vorgang zum Erstellen einer Momentaufnahme des BLOBs.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SnapshotAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlob&gt; SnapshotAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.CloudBlob&gt; SnapshotAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.SnapshotAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SnapshotAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlob&gt;&#xA;override this.SnapshotAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlob&gt;" Usage="cloudBlob.SnapshotAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Erstellen einer Momentaufnahme des BLOBs.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SnapshotAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlob&gt; SnapshotAsync (System.Collections.Generic.IDictionary&lt;string,string&gt; metadata, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.CloudBlob&gt; SnapshotAsync(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; metadata, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.SnapshotAsync(System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SnapshotAsync : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlob&gt;&#xA;override this.SnapshotAsync : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlob&gt;" Usage="cloudBlob.SnapshotAsync (metadata, accessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="metadata" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="metadata">Eine Auflistung von Name-Wert-Paare definieren die Metadaten der Momentaufnahme.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Erstellen einer Momentaufnahme des BLOBs.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SnapshotAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlob&gt; SnapshotAsync (System.Collections.Generic.IDictionary&lt;string,string&gt; metadata, Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Blob.CloudBlob&gt; SnapshotAsync(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; metadata, class Microsoft.WindowsAzure.Storage.AccessCondition accessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.SnapshotAsync(System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SnapshotAsync : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlob&gt;&#xA;override this.SnapshotAsync : System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlob&gt;" Usage="cloudBlob.SnapshotAsync (metadata, accessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="metadata" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="accessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="metadata">Eine Auflistung von Name-Wert-Paare definieren die Metadaten der Momentaufnahme.</param>
        <param name="accessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die Bedingung, die erfüllt sein müssen, damit die Anforderung darstellt, um den Vorgang fortzusetzen. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Erstellen einer Momentaufnahme des BLOBs.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlob" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SnapshotQualifiedStorageUri">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.StorageUri SnapshotQualifiedStorageUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.StorageUri SnapshotQualifiedStorageUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.SnapshotQualifiedStorageUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SnapshotQualifiedStorageUri As StorageUri" />
      <MemberSignature Language="F#" Value="member this.SnapshotQualifiedStorageUri : Microsoft.WindowsAzure.Storage.StorageUri" Usage="Microsoft.WindowsAzure.Storage.Blob.CloudBlob.SnapshotQualifiedStorageUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.StorageUri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den URI des BLOBs für die primären und sekundären Speicherorte, einschließlich abfragezeichenfolgeinformationen, wenn das Blob eine Momentaufnahme ist.
            </summary>
        <value>Ein Objekt des Typs <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.StorageUri" /> , enthält die Blob-URIs für die primären und sekundären Speicherorte, einschließlich momentaufnahmeabfrageinformationen, wenn das Blob eine Momentaufnahme ist.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SnapshotQualifiedUri">
      <MemberSignature Language="C#" Value="public Uri SnapshotQualifiedUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri SnapshotQualifiedUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.SnapshotQualifiedUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SnapshotQualifiedUri As Uri" />
      <MemberSignature Language="F#" Value="member this.SnapshotQualifiedUri : Uri" Usage="Microsoft.WindowsAzure.Storage.Blob.CloudBlob.SnapshotQualifiedUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den absoluten URI zum Blob, einschließlich abfragezeichenfolgeinformationen, wenn das Blob eine Momentaufnahme ist.
            </summary>
        <value>Ein <see cref="T:System.Uri" /> angeben den absoluten URI zum Blob, einschließlich momentaufnahmeabfrageinformationen, wenn das Blob eine Momentaufnahme ist.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SnapshotTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; SnapshotTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; SnapshotTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.SnapshotTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SnapshotTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.SnapshotTime : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.CloudBlob.SnapshotTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Datum und die Uhrzeit, zu der die Blob-Momentaufnahme erstellt wurde, ab, wenn dieses Blob eine Momentaufnahme ist.
            </summary>
        <value>Ein <see cref="T:System.DateTimeOffset" /> , die das Blob enthält der Momentaufnahme, wenn das Blob eine Momentaufnahme ist, andernfalls <c>null</c>.</value>
        <remarks>
            Wenn das Blob keine Momentaufnahme ist, ist der Wert dieser Eigenschaft <c>null</c>.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartCopy">
      <MemberSignature Language="C#" Value="public virtual string StartCopy (Uri source, Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition = null, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition = null, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string StartCopy(class System.Uri source, class Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.StartCopy(System.Uri,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member StartCopy : Uri * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; string&#xA;override this.StartCopy : Uri * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; string" Usage="cloudBlob.StartCopy (source, sourceAccessCondition, destAccessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.Uri" />
        <Parameter Name="sourceAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="destAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="source">Die <see cref="T:System.Uri" /> des Quell-Blob.</param>
        <param name="sourceAccessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die zugriffsbedingungen für das Quell-Blob darstellt. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="destAccessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die zugriffsbedingungen für das Ziel-Blob darstellt. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt. Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Startet einen Vorgang zum Starten des Blob-Inhalte, Eigenschaften und Metadaten in dieses Blob kopiert.
            </summary>
        <returns>Der Kopiervorgang zugeordnete Kopie-ID.</returns>
        <remarks>
            Diese Methode ruft die Blob-ETag, Uhrzeit der letzten Änderung und Teil den Kopierstatus ab.
            Die Kopie-ID und kopieren Sie den Statusfeldern abgerufen werden, und die restliche den Kopierstatus deaktiviert ist.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartCopyAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; StartCopyAsync (Uri source);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; StartCopyAsync(class System.Uri source) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.StartCopyAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function StartCopyAsync (source As Uri) As Task(Of String)" />
      <MemberSignature Language="F#" Value="abstract member StartCopyAsync : Uri -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.StartCopyAsync : Uri -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlob.StartCopyAsync source" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="source">Die <see cref="T:System.Uri" /> des Quell-Blob.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Starten des Blob-Inhalte, Eigenschaften und Metadaten in dieses Blob kopiert.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Zeichenfolge</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartCopyAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; StartCopyAsync (Uri source, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; StartCopyAsync(class System.Uri source, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.StartCopyAsync(System.Uri,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StartCopyAsync : Uri * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.StartCopyAsync : Uri * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlob.StartCopyAsync (source, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.Uri" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source">Die <see cref="T:System.Uri" /> des Quell-Blob.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Starten des Blob-Inhalte, Eigenschaften und Metadaten in dieses Blob kopiert.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Zeichenfolge</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartCopyAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; StartCopyAsync (Uri source, Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; StartCopyAsync(class System.Uri source, class Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.StartCopyAsync(System.Uri,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member StartCopyAsync : Uri * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.StartCopyAsync : Uri * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlob.StartCopyAsync (source, sourceAccessCondition, destAccessCondition, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.Uri" />
        <Parameter Name="sourceAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="destAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="source">Die <see cref="T:System.Uri" /> des Quell-Blob.</param>
        <param name="sourceAccessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die zugriffsbedingungen für das Quell-Blob darstellt. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="destAccessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die zugriffsbedingungen für das Ziel-Blob darstellt. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Starten des Blob-Inhalte, Eigenschaften und Metadaten in dieses Blob kopiert.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Zeichenfolge</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartCopyAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;string&gt; StartCopyAsync (Uri source, Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; StartCopyAsync(class System.Uri source, class Microsoft.WindowsAzure.Storage.AccessCondition sourceAccessCondition, class Microsoft.WindowsAzure.Storage.AccessCondition destAccessCondition, class Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.StartCopyAsync(System.Uri,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.AccessCondition,Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StartCopyAsync : Uri * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.StartCopyAsync : Uri * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.AccessCondition * Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="cloudBlob.StartCopyAsync (source, sourceAccessCondition, destAccessCondition, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="source" Type="System.Uri" />
        <Parameter Name="sourceAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="destAccessCondition" Type="Microsoft.WindowsAzure.Storage.AccessCondition" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="source">Die <see cref="T:System.Uri" /> des Quell-Blob.</param>
        <param name="sourceAccessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die zugriffsbedingungen für das Quell-Blob darstellt. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="destAccessCondition">Ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die zugriffsbedingungen für das Ziel-Blob darstellt. Wenn <c>null</c>, keine Bedingung verwendet.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Starten des Blob-Inhalte, Eigenschaften und Metadaten in dieses Blob kopiert.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Zeichenfolge</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageUri">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.StorageUri StorageUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.StorageUri StorageUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.StorageUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageUri As StorageUri" />
      <MemberSignature Language="F#" Value="member this.StorageUri : Microsoft.WindowsAzure.Storage.StorageUri" Usage="Microsoft.WindowsAzure.Storage.Blob.CloudBlob.StorageUri" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.Blob.IListBlobItem.StorageUri</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.StorageUri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Blob-URIs für die primären und sekundären Speicherorte ab.
            </summary>
        <value>Ein Objekt des Typs <see cref="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.StorageUri" /> , das Blob-URIs für die primären und sekundären Speicherorte enthält.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StreamMinimumReadSizeInBytes">
      <MemberSignature Language="C#" Value="public int StreamMinimumReadSizeInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 StreamMinimumReadSizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.StreamMinimumReadSizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property StreamMinimumReadSizeInBytes As Integer" />
      <MemberSignature Language="F#" Value="member this.StreamMinimumReadSizeInBytes : int with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.CloudBlob.StreamMinimumReadSizeInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Mindestanzahl von Bytes, die beim Lesen aus einem blobdatenstrom gepuffert werden sollen.
            </summary>
        <value>Die minimale Anzahl von Bytes zu puffernder mindestens 16 KB.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Uri">
      <MemberSignature Language="C#" Value="public Uri Uri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Uri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.CloudBlob.Uri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Uri As Uri" />
      <MemberSignature Language="F#" Value="member this.Uri : Uri" Usage="Microsoft.WindowsAzure.Storage.Blob.CloudBlob.Uri" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.Blob.IListBlobItem.Uri</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft URIs des BLOBs für den primären Speicherort ab.
            </summary>
        <value>Ein <see cref="T:System.Uri" /> , der den absoluten URI zum Blob am primären Speicherort angibt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
