<Type Name="BlobRequestOptions" FullName="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions">
  <TypeSignature Language="C#" Value="public sealed class BlobRequestOptions : Microsoft.WindowsAzure.Storage.IRequestOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit BlobRequestOptions extends System.Object implements class Microsoft.WindowsAzure.Storage.IRequestOptions" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class BlobRequestOptions&#xA;Implements IRequestOptions" />
  <TypeSignature Language="F#" Value="type BlobRequestOptions = class&#xA;    interface IRequestOptions" />
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
      <InterfaceName>Microsoft.WindowsAzure.Storage.IRequestOptions</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Stellt eine Reihe von Optionen für Timeout- und wiederholungsrichtlinien, die für eine Anforderung für den Blob-Dienst angegeben werden kann.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BlobRequestOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AbsorbConditionalErrorsOnRetry">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AbsorbConditionalErrorsOnRetry { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AbsorbConditionalErrorsOnRetry" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />
      <MemberSignature Language="VB.NET" Value="Public Property AbsorbConditionalErrorsOnRetry As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AbsorbConditionalErrorsOnRetry : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.AbsorbConditionalErrorsOnRetry" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert, der angibt, ob bei einem Wiederholungsversuch für die Anforderung ein bedingten Fehler aufgenommen werden sollten. 
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Option wird nur von verwendet die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> Objekt in der <b>UploadFrom* </b> Methoden, die <b>AppendFrom* </b> Methoden, und die <b>BlobWriteStream</b> Klasse. Standardmäßig wird es auf festgelegt, <c>"false"</c>. Legen Sie diese Option, um <c>"true"</c> nur für einzelne Writer-Szenarien. Wenn diese Option auf <c>"true"</c> in einem Szenario mit mehreren Writer kann auf beschädigte Blob-Daten führen.
            
            "UploadFrom *" auf ein Anhang-Blob aufrufen, der Speicherclient die Eingabedaten in eine Anzahl von Datenblöcken unterbrochen, und Hochladen der einzelnen Datenblöcke mit einer "Append Block"-Operation.
            Eine zugriffsbedingung "IfAppendPositionEqual" ist in der Regel wird der Block-Anfügevorgang hinzugefügt, damit der Uploadvorgang fehl, wenn ein anderer Prozess an einer beliebigen Stelle Daten in der Mitte diesen Datenstream angefügt wurde.
            Allerdings kann dies in einem sehr spezifischen Szenario "false" zu einem Fehler führen. Fällt ein Anfügevorgang mit einem Timeout, besteht die Möglichkeit, die auf dem Dienst der Vorgang erfolgreich war, aber die Antwort "Success" nicht unbedingt an dem Client zurück.
            In diesem Fall wird der Client erneut, und rufen dann einen "append Position nicht erfüllt" Fehler.
            
            Wenn dieser Wert auf <c>"true"</c> führt zu den Uploadvorgang fortsetzen, wenn sie einen "append Position nicht erfüllt" Fehler bei der Wiederholung - Kontoführung für die oben genannten Möglichkeit sieht. Allerdings dies Schutz im Szenario mit mehreren Writer - verloren, wenn mehrere Threads gleichzeitig in das Blob hochgeladen werden, und dieser Wert, um festgelegt wird <c>"true"</c>, einige Daten verloren, da der Client nimmt die Daten wurde hochgeladen, wenn in der Tat wurde der andere Prozess Daten.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableContentMD5Validation">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; DisableContentMD5Validation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; DisableContentMD5Validation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.DisableContentMD5Validation" />
      <MemberSignature Language="VB.NET" Value="Public Property DisableContentMD5Validation As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.DisableContentMD5Validation : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.DisableContentMD5Validation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert fest, um anzugeben, dass die MD5-Überprüfung beim Herunterladen von Blobs deaktiviert wird.
            </summary>
        <value>Verwendung <c>"true"</c> MD5-Prüfung, deaktivieren <c>"false"</c> MD5-Überprüfung zu aktivieren. Die Standardeinstellung lautet <c>false</c>.</value>
        <remarks>
            Wenn ein Blob herunterladen, wenn der Wert für das Blob bereits vorhanden ist, wird der Speicherdienst den MD5-Hash, der das gesamte Blob als einen Header enthalten. Dieser Option wird gesteuert, und zwar unabhängig davon, ob der Speicherclient auf Download, MD5-Hash überprüft.
            Ausführliche Informationen finden Sie unter <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.StoreBlobContentMD5" />.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.BlobEncryptionPolicy EncryptionPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Blob.BlobEncryptionPolicy EncryptionPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.EncryptionPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionPolicy As BlobEncryptionPolicy" />
      <MemberSignature Language="F#" Value="member this.EncryptionPolicy : Microsoft.WindowsAzure.Storage.Blob.BlobEncryptionPolicy with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.EncryptionPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlobEncryptionPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Verschlüsselungsrichtlinie für die Anforderung.
            </summary>
        <value>Ein Objekt vom Typ <see cref="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.EncryptionPolicy" />.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocationMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode&gt; LocationMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode&gt; LocationMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.LocationMode" />
      <MemberSignature Language="VB.NET" Value="Public Property LocationMode As Nullable(Of LocationMode)" />
      <MemberSignature Language="F#" Value="member this.LocationMode : Nullable&lt;Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.LocationMode" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.IRequestOptions.LocationMode</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             Ruft ab oder legt den Positionsmodus der Anforderung fest.
             </summary>
        <value>Ein <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode" /> -Enumerationswert, der angibt, des Positionsmodus der Anforderung.</value>
        <remarks>Die LocationMode gibt an, in dem Speicherorte der Storage Client versucht, für die Anforderung. Dies gilt nur für Konten für RA-GRS - Konten, in denen Daten aus der primären oder sekundären Endpunkt gelesen werden kann.
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumExecutionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; MaximumExecutionTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; MaximumExecutionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.MaximumExecutionTime" />
      <MemberSignature Language="VB.NET" Value="Public Property MaximumExecutionTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.MaximumExecutionTime : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.MaximumExecutionTime" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.IRequestOptions.MaximumExecutionTime</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die maximale Ausführungszeit für alle möglichen Wiederholungen für die Anforderung. 
            </summary>
        <value>Ein <see cref="T:System.TimeSpan" /> , die die maximale Ausführungszeit für Wiederholungen für die Anforderung darstellt.</value>
        <remarks>
            Die maximale Ausführungszeit werden für einen einzelnen API-Aufruf zugeteilt.
            Wenn der insgesamt in der API - für alle übrigen Anforderungen aufgewendete Zeit Wiederholungen usw. -diesen Wert überschreitet, tritt ein Timeout des Clients. Dieser Wert nur auf dem Client verfolgt wird, ist es nicht an den Dienst gesendet.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ParallelOperationThreadCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ParallelOperationThreadCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ParallelOperationThreadCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.ParallelOperationThreadCount" />
      <MemberSignature Language="VB.NET" Value="Public Property ParallelOperationThreadCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ParallelOperationThreadCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.ParallelOperationThreadCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             Ruft ab oder legt die Anzahl der Blöcke, die gleichzeitig hochgeladen werden können.
             </summary>
        <value>Ein ganzzahliger Wert, der angibt, der Anzahl der parallelen blobhochladevorgänge upload-Vorgänge, die fortgesetzt werden können.</value>
        <remarks>
             Wenn Sie die UploadFrom *-Methoden für ein Blob zu verwenden, wird das Blob in Blöcke aufgeteilt werden. Das Festlegen dieser Grenzwerte, die die Anzahl der ausstehenden e/a-"put Block" fordert, dass die Bibliothek zu einem bestimmten Zeitpunkt in-Flight aufweist. Standard ist 1 (keine Parallelität). Erhöhen des Werts möglicherweise schneller Blob-Uploads, je nach im Netzwerk zwischen dem Client und dem Azure Storage-Dienst.
             Wenn Blobs sind klein (weniger als 256 MB), lassen diesen Wert gleich 1 wird abgeraten.
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="RequireEncryption">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RequireEncryption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RequireEncryption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.RequireEncryption" />
      <MemberSignature Language="VB.NET" Value="Public Property RequireEncryption As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RequireEncryption : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.RequireEncryption" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.IRequestOptions.RequireEncryption</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert anzugeben, ob die Daten geschrieben und gelesen werden, von der Clientbibliothek verschlüsselt werden sollen.
            </summary>
        <value>Verwendung <c>"true"</c> um anzugeben, dass die Daten werden soll, für alle Transaktionen verschlüsselt und entschlüsselt, und andernfalls <c>"false"</c>.</value>
        <remarks>
            Hier RequireEncryption bezieht sich auf Client-seitige Ver-.
            Wenn dieser Wert, um festgelegt wird <c>"true"</c>, alle Aufrufe schlagen fehl, wenn die Daten nicht mit einer Verschlüsselungsrichtlinie verschlüsselt und entschlüsselt sind. Wenn dieser Wert "false" (Standard), alle Daten, die heruntergeladen werden, die nicht verschlüsselt ist, wird als zurückgegeben-ist.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy RetryPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy RetryPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.RetryPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryPolicy As IRetryPolicy" />
      <MemberSignature Language="F#" Value="member this.RetryPolicy : Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.RetryPolicy" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.IRequestOptions.RetryPolicy</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             Ruft ab oder legt die wiederholungsrichtlinie für die Anforderung.
             </summary>
        <value>Ein Objekt vom Typ <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" />.</value>
        <remarks> Wiederholungsrichtlinien weisen die Storage Client um Anforderungsfehler zu wiederholen.
             Standardmäßig werden nur einige Fehler wiederholt. Beispielsweise können Verbindungsfehler und Drosselung Fehlern wiederholt werden. Ressource nicht gefunden (404) oder Authentifizierungsfehler nicht wiederholt, da keine wahrscheinlich bei der Wiederholung erfolgreich sind.
             Wenn dies nicht festgelegt ist, der Storage Client verwendet eine exponentiellen Backoff-wiederholungsrichtlinie, ruft die Wartezeit exponentiell länger zwischen den Anforderungen, bis zu einer Summe von ca. 30 Sekunden.
             Die standardmäßige wiederholungsrichtlinie wird in den meisten Szenarien empfohlen.
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; ServerTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; ServerTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.ServerTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property ServerTimeout As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.ServerTimeout : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.ServerTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.IRequestOptions.ServerTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Servertimeout-Intervall für eine einzelne HTTP-Anforderung.
            </summary>
        <value>Ein <see cref="T:System.TimeSpan" /> mit dem servertimeoutintervall für jede HTTP-Anforderung.</value>
        <remarks>
            Das Servertimeout beträgt das Timeout an den Azure Storage-Dienst für jeden REST-Anforderung gesendet. Wenn die API namens mehrere REST-Aufrufe vornimmt (UploadFromStream, z. B. oder wenn die Anforderung wiederholt), dieses Timeout wird separat für jede Anforderung angewendet werden. Dieser Wert nicht nachverfolgt werden oder auf dem Client überprüft, es wird nur in den Speicherdienst übergeben.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SingleBlobUploadThresholdInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; SingleBlobUploadThresholdInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; SingleBlobUploadThresholdInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.SingleBlobUploadThresholdInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property SingleBlobUploadThresholdInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.SingleBlobUploadThresholdInBytes : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.SingleBlobUploadThresholdInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die maximale Größe eines BLOBs in Byte, die als einzelnes Blob hochgeladen werden kann. 
            </summary>
        <value>Ein Long-Wert, der angibt, der maximalen Größe eines BLOBs, in Bytes, der als einzelnes Blob im Bereich von 1 und 256 MB liegen einschließlich hochgeladen werden kann.</value>
        <remarks>Dieser Wert wird ignoriert, wenn die ParallelOperationThreadCount auf einen Wert größer als 1 festgelegt ist</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoreBlobContentMD5">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; StoreBlobContentMD5 { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; StoreBlobContentMD5" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.StoreBlobContentMD5" />
      <MemberSignature Language="VB.NET" Value="Public Property StoreBlobContentMD5 As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.StoreBlobContentMD5 : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.StoreBlobContentMD5" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert fest, um anzugeben, dass ein MD5-Hash berechnet und gespeichert, wenn einen Blob hochladen.
            </summary>
        <value>Verwendung <c>"true"</c> zum Berechnen und speichern einen MD5-Hash beim Hochladen eines BLOBs; andernfalls <c>"false"</c>. Standardmäßig <c>"false"</c>.</value>
        <remarks>Diese Eigenschaft wird nicht unterstützt, für die <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudAppendBlob" /> Append * APIs.
            Die Option zur StoreBlobContentMD5 weist die Storage Client während eines Vorgangs Upload den MD5-Hash des Blob-Inhalts zu berechnen. Dieser Wert wird dann als Content-MD5-Header für das Blob gespeichert. Diese Option gilt nur, um Vorgänge hochzuladen. Dies ist nützlich beim Überprüfen der Integrität des Blob bei späteren herunterladen und mit der Content-MD5-Header, gemäß Definition in der HTTP-Spezifikation kompatibel. Wenn der Speicherclient für spätere herunterladen, wenn der Content-MD5-Header vorhanden ist, wird der MD5-Hash des Inhalts überprüft werden, es sei denn, "DisableContentMD5Validation" festgelegt ist.
            Beachten Sie, dass dieser Wert auf den Azure-Speicherdienst hochladen oder Herunterladen von Daten nicht überprüft wird. Er ist lediglich gespeichert und zurückgegeben.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UseTransactionalMD5">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; UseTransactionalMD5 { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; UseTransactionalMD5" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.UseTransactionalMD5" />
      <MemberSignature Language="VB.NET" Value="Public Property UseTransactionalMD5 As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.UseTransactionalMD5 : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobRequestOptions.UseTransactionalMD5" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert berechnen und Senden/prüfen von Inhalts-MD5 für Transaktionen.
            </summary>
        <value>Verwendung <c>"true"</c> zu berechnen und Senden/prüfen von Inhalts-MD5 für Transaktionen; andernfalls <c>"false"</c>. Die Standardeinstellung lautet <c>false</c>.</value>
        <remarks>
            Die UseTransactionalMD5-Option weist der Speicherclient berechnet und überprüft den MD5-Hash der einzelnen Speicher REST-Vorgänge. Für einen angegebenen REST-Vorgang Wenn dieser Wert festgelegt ist, sowohl die Storage Client den Speicherdienst berechnet den MD5-Hash der übertragenen Daten und schlägt fehl, wenn die Werte nicht übereinstimmen.
            Dieser Wert wird auf den Dienst oder der Client nicht beibehalten.
            Diese Option gilt für sowohl upload und download-Vorgänge.
            Beachten Sie, dass HTTPS eine ähnliche Überprüfung während der Übertragung verwendet wird. Wenn Sie HTTPS verwenden, wird empfohlen, dass diese Funktion deaktiviert werden.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>