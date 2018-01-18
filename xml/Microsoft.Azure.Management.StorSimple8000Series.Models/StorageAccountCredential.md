<Type Name="StorageAccountCredential" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential">
  <TypeSignature Language="C#" Value="public class StorageAccountCredential : Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StorageAccountCredential extends Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential" />
  <TypeSignature Language="VB.NET" Value="Public Class StorageAccountCredential&#xA;Inherits BaseModel" />
  <TypeSignature Language="F#" Value="type StorageAccountCredential = class&#xA;    inherit BaseModel" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="cdadc-101">Der Speicherkonto-Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="cdadc-101">The storage account credential.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccountCredential ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="cdadc-102">Initialisiert eine neue Instanz der StorageAccountCredential-Klasse.</span><span class="sxs-lookup"><span data-stu-id="cdadc-102">Initializes a new instance of the StorageAccountCredential class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccountCredential (string endPoint, Microsoft.Azure.Management.StorSimple8000Series.Models.SslStatus sslStatus, string id = null, string name = null, string type = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind = null, Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret accessKey = null, Nullable&lt;int&gt; volumesCount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string endPoint, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.SslStatus sslStatus, string id, string name, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind, class Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret accessKey, valuetype System.Nullable`1&lt;int32&gt; volumesCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential.#ctor(System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.SslStatus,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.Kind},Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret,System.Nullable{System.Int32})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential : string * Microsoft.Azure.Management.StorSimple8000Series.Models.SslStatus * string * string * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; * Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential (endPoint, sslStatus, id, name, type, kind, accessKey, volumesCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="endPoint" Type="System.String" />
        <Parameter Name="sslStatus" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.SslStatus" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt;" />
        <Parameter Name="accessKey" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret" />
        <Parameter Name="volumesCount" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="endPoint"><span data-ttu-id="cdadc-103">Der speicherendpunkt</span><span class="sxs-lookup"><span data-stu-id="cdadc-103">The storage endpoint</span></span></param>
        <param name="sslStatus"><span data-ttu-id="cdadc-104">Gibt an, ob SSL aktiviert oder deaktiviert werden muss.</span><span class="sxs-lookup"><span data-stu-id="cdadc-104">Signifies whether SSL needs to be enabled or not.</span></span> <span data-ttu-id="cdadc-105">Folgende Werte sind möglich: "Enabled", "Disabled"</span><span class="sxs-lookup"><span data-stu-id="cdadc-105">Possible values include: 'Enabled', 'Disabled'</span></span></param>
        <param name="id"><span data-ttu-id="cdadc-106">Die Pfad-ID, die das Objekt eindeutig identifiziert.</span><span class="sxs-lookup"><span data-stu-id="cdadc-106">The path ID that uniquely identifies the object.</span></span></param>
        <param name="name"><span data-ttu-id="cdadc-107">Der Name des Objekts.</span><span class="sxs-lookup"><span data-stu-id="cdadc-107">The name of the object.</span></span></param>
        <param name="type"><span data-ttu-id="cdadc-108">Der hierarchische Typ des Objekts.</span><span class="sxs-lookup"><span data-stu-id="cdadc-108">The hierarchical type of the object.</span></span></param>
        <param name="kind"><span data-ttu-id="cdadc-109">Die Art des Objekts.</span><span class="sxs-lookup"><span data-stu-id="cdadc-109">The Kind of the object.</span></span> <span data-ttu-id="cdadc-110">Derzeit wird nur Series8000 wird unterstützt.</span><span class="sxs-lookup"><span data-stu-id="cdadc-110">Currently only Series8000 is supported.</span></span> <span data-ttu-id="cdadc-111">Folgende Werte sind möglich: "Series8000"</span><span class="sxs-lookup"><span data-stu-id="cdadc-111">Possible values include: 'Series8000'</span></span></param>
        <param name="accessKey"><span data-ttu-id="cdadc-112">Die Details der das Kennwort für das Speicherkonto.</span><span class="sxs-lookup"><span data-stu-id="cdadc-112">The details of the storage account password.</span></span></param>
        <param name="volumesCount"><span data-ttu-id="cdadc-113">Die Anzahl der Volumes, verwenden die Anmeldeinformationen dieses Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="cdadc-113">The count of volumes using this storage account credential.</span></span></param>
        <summary>
            <span data-ttu-id="cdadc-114">Initialisiert eine neue Instanz der StorageAccountCredential-Klasse.</span><span class="sxs-lookup"><span data-stu-id="cdadc-114">Initializes a new instance of the StorageAccountCredential class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret AccessKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret AccessKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential.AccessKey" />
      <MemberSignature Language="VB.NET" Value="Public Property AccessKey As AsymmetricEncryptedSecret" />
      <MemberSignature Language="F#" Value="member this.AccessKey : Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential.AccessKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.accessKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cdadc-115">Ermittelt oder definiert die Details der das Kennwort für das Speicherkonto.</span><span class="sxs-lookup"><span data-stu-id="cdadc-115">Gets or sets the details of the storage account password.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndPoint">
      <MemberSignature Language="C#" Value="public string EndPoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EndPoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential.EndPoint" />
      <MemberSignature Language="VB.NET" Value="Public Property EndPoint As String" />
      <MemberSignature Language="F#" Value="member this.EndPoint : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential.EndPoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.endPoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cdadc-116">Ruft ab oder legt die Speicherkonto-Endpunkt</span><span class="sxs-lookup"><span data-stu-id="cdadc-116">Gets or sets the storage endpoint</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SslStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.SslStatus SslStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.SslStatus SslStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential.SslStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property SslStatus As SslStatus" />
      <MemberSignature Language="F#" Value="member this.SslStatus : Microsoft.Azure.Management.StorSimple8000Series.Models.SslStatus with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential.SslStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sslStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.SslStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cdadc-117">Gibt an, ob SSL aktiviert oder deaktiviert werden muss, ruft ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="cdadc-117">Gets or sets signifies whether SSL needs to be enabled or not.</span></span>
            <span data-ttu-id="cdadc-118">Folgende Werte sind möglich: "Enabled", "Disabled"</span><span class="sxs-lookup"><span data-stu-id="cdadc-118">Possible values include: 'Enabled', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="storageAccountCredential.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="cdadc-119">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="cdadc-119">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="cdadc-120">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="cdadc-120">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VolumesCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; VolumesCount { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; VolumesCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential.VolumesCount" />
      <MemberSignature Language="VB.NET" Value="Public Property VolumesCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.VolumesCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential.VolumesCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.volumesCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cdadc-121">Ruft die Anzahl der Volumes, verwenden die Anmeldeinformationen dieses Speicherkontos ab.</span><span class="sxs-lookup"><span data-stu-id="cdadc-121">Gets the count of volumes using this storage account credential.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>