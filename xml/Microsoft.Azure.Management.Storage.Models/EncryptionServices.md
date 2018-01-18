<Type Name="EncryptionServices" FullName="Microsoft.Azure.Management.Storage.Models.EncryptionServices">
  <TypeSignature Language="C#" Value="public class EncryptionServices" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EncryptionServices extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Models.EncryptionServices" />
  <TypeSignature Language="VB.NET" Value="Public Class EncryptionServices" />
  <TypeSignature Language="F#" Value="type EncryptionServices = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
    <AssemblyVersion>7.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="19bb4-101">Eine Liste der Dienste, die Verschlüsselung zu unterstützen.</span><span class="sxs-lookup"><span data-stu-id="19bb4-101">A list of services that support encryption.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EncryptionServices ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.EncryptionServices.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="19bb4-102">Initialisiert eine neue Instanz der EncryptionServices-Klasse.</span><span class="sxs-lookup"><span data-stu-id="19bb4-102">Initializes a new instance of the EncryptionServices class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EncryptionServices (Microsoft.Azure.Management.Storage.Models.EncryptionService blob = null, Microsoft.Azure.Management.Storage.Models.EncryptionService file = null, Microsoft.Azure.Management.Storage.Models.EncryptionService table = null, Microsoft.Azure.Management.Storage.Models.EncryptionService queue = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Storage.Models.EncryptionService blob, class Microsoft.Azure.Management.Storage.Models.EncryptionService file, class Microsoft.Azure.Management.Storage.Models.EncryptionService table, class Microsoft.Azure.Management.Storage.Models.EncryptionService queue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.EncryptionServices.#ctor(Microsoft.Azure.Management.Storage.Models.EncryptionService,Microsoft.Azure.Management.Storage.Models.EncryptionService,Microsoft.Azure.Management.Storage.Models.EncryptionService,Microsoft.Azure.Management.Storage.Models.EncryptionService)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional blob As EncryptionService = null, Optional file As EncryptionService = null, Optional table As EncryptionService = null, Optional queue As EncryptionService = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Storage.Models.EncryptionServices : Microsoft.Azure.Management.Storage.Models.EncryptionService * Microsoft.Azure.Management.Storage.Models.EncryptionService * Microsoft.Azure.Management.Storage.Models.EncryptionService * Microsoft.Azure.Management.Storage.Models.EncryptionService -&gt; Microsoft.Azure.Management.Storage.Models.EncryptionServices" Usage="new Microsoft.Azure.Management.Storage.Models.EncryptionServices (blob, file, table, queue)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="blob" Type="Microsoft.Azure.Management.Storage.Models.EncryptionService" />
        <Parameter Name="file" Type="Microsoft.Azure.Management.Storage.Models.EncryptionService" />
        <Parameter Name="table" Type="Microsoft.Azure.Management.Storage.Models.EncryptionService" />
        <Parameter Name="queue" Type="Microsoft.Azure.Management.Storage.Models.EncryptionService" />
      </Parameters>
      <Docs>
        <param name="blob"><span data-ttu-id="19bb4-103">Die Verschlüsselungsfunktion von Blob-Speicherdienst.</span><span class="sxs-lookup"><span data-stu-id="19bb4-103">The encryption function of the blob storage service.</span></span></param>
        <param name="file"><span data-ttu-id="19bb4-104">Die Verschlüsselungsfunktion des dateidiensts Speicher.</span><span class="sxs-lookup"><span data-stu-id="19bb4-104">The encryption function of the file storage service.</span></span></param>
        <param name="table"><span data-ttu-id="19bb4-105">Die Verschlüsselungsfunktion des tabellendiensts Speicher.</span><span class="sxs-lookup"><span data-stu-id="19bb4-105">The encryption function of the table storage service.</span></span></param>
        <param name="queue"><span data-ttu-id="19bb4-106">Die Verschlüsselungsfunktion des warteschlangenspeicherdiensts.</span><span class="sxs-lookup"><span data-stu-id="19bb4-106">The encryption function of the queue storage service.</span></span></param>
        <summary>
            <span data-ttu-id="19bb4-107">Initialisiert eine neue Instanz der EncryptionServices-Klasse.</span><span class="sxs-lookup"><span data-stu-id="19bb4-107">Initializes a new instance of the EncryptionServices class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Blob">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.EncryptionService Blob { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Models.EncryptionService Blob" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.EncryptionServices.Blob" />
      <MemberSignature Language="VB.NET" Value="Public Property Blob As EncryptionService" />
      <MemberSignature Language="F#" Value="member this.Blob : Microsoft.Azure.Management.Storage.Models.EncryptionService with get, set" Usage="Microsoft.Azure.Management.Storage.Models.EncryptionServices.Blob" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="blob")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.EncryptionService</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="19bb4-108">Ruft ab oder legt die Encryption-Funktion von Blob-Speicherdienst.</span><span class="sxs-lookup"><span data-stu-id="19bb4-108">Gets or sets the encryption function of the blob storage service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="File">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.EncryptionService File { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Models.EncryptionService File" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.EncryptionServices.File" />
      <MemberSignature Language="VB.NET" Value="Public Property File As EncryptionService" />
      <MemberSignature Language="F#" Value="member this.File : Microsoft.Azure.Management.Storage.Models.EncryptionService with get, set" Usage="Microsoft.Azure.Management.Storage.Models.EncryptionServices.File" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="file")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.EncryptionService</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="19bb4-109">Abrufen oder festlegen die Verschlüsselungsfunktion des dateidiensts Speicher.</span><span class="sxs-lookup"><span data-stu-id="19bb4-109">Gets or sets the encryption function of the file storage service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Queue">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.EncryptionService Queue { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Models.EncryptionService Queue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.EncryptionServices.Queue" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Queue As EncryptionService" />
      <MemberSignature Language="F#" Value="member this.Queue : Microsoft.Azure.Management.Storage.Models.EncryptionService" Usage="Microsoft.Azure.Management.Storage.Models.EncryptionServices.Queue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="queue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.EncryptionService</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="19bb4-110">Ruft die Verschlüsselungsfunktion des Warteschlangenspeicher-Diensts ab.</span><span class="sxs-lookup"><span data-stu-id="19bb4-110">Gets the encryption function of the queue storage service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Table">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.EncryptionService Table { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Models.EncryptionService Table" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.EncryptionServices.Table" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Table As EncryptionService" />
      <MemberSignature Language="F#" Value="member this.Table : Microsoft.Azure.Management.Storage.Models.EncryptionService" Usage="Microsoft.Azure.Management.Storage.Models.EncryptionServices.Table" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="table")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.EncryptionService</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="19bb4-111">Ruft die Encryption-Funktion des tabellendiensts Speicher ab.</span><span class="sxs-lookup"><span data-stu-id="19bb4-111">Gets the encryption function of the table storage service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>