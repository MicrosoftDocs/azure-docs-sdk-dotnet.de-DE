<Type Name="StorageEndpointProperties" FullName="Microsoft.Azure.Management.IotHub.Models.StorageEndpointProperties">
  <TypeSignature Language="C#" Value="public class StorageEndpointProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StorageEndpointProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.Models.StorageEndpointProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class StorageEndpointProperties" />
  <TypeSignature Language="F#" Value="type StorageEndpointProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="25258-101">Die Eigenschaften des Azure-Speicher-Endpunkts für die Datei hochgeladen werden.</span><span class="sxs-lookup"><span data-stu-id="25258-101">The properties of the Azure Storage endpoint for file upload.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageEndpointProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.StorageEndpointProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="25258-102">Initialisiert eine neue Instanz der StorageEndpointProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="25258-102">Initializes a new instance of the StorageEndpointProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageEndpointProperties (string connectionString, string containerName, Nullable&lt;TimeSpan&gt; sasTtlAsIso8601 = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString, string containerName, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; sasTtlAsIso8601) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.StorageEndpointProperties.#ctor(System.String,System.String,System.Nullable{System.TimeSpan})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (connectionString As String, containerName As String, Optional sasTtlAsIso8601 As Nullable(Of TimeSpan) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.IotHub.Models.StorageEndpointProperties : string * string * Nullable&lt;TimeSpan&gt; -&gt; Microsoft.Azure.Management.IotHub.Models.StorageEndpointProperties" Usage="new Microsoft.Azure.Management.IotHub.Models.StorageEndpointProperties (connectionString, containerName, sasTtlAsIso8601)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="sasTtlAsIso8601" Type="System.Nullable&lt;System.TimeSpan&gt;" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="25258-103">Die Verbindungszeichenfolge für das Azure-Speicherkonto auf dem Dateien hochgeladen werden.</span><span class="sxs-lookup"><span data-stu-id="25258-103">The connection string for the Azure Storage account to which files are uploaded.</span></span></param>
        <param name="containerName"><span data-ttu-id="25258-104">Der Name des Stammcontainers, in dem Sie Dateien hochladen.</span><span class="sxs-lookup"><span data-stu-id="25258-104">The name of the root container where you upload files.</span></span> <span data-ttu-id="25258-105">Der Container muss nicht vorhanden, aber sollten erstellt mithilfe der "ConnectionString" angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="25258-105">The container need not exist but should be creatable using the connectionString specified.</span></span></param>
        <param name="sasTtlAsIso8601"><span data-ttu-id="25258-106">Der Zeitraum für die die der SAS-URI generiert durch den IoT Hub Dateiupload ist ungültig.</span><span class="sxs-lookup"><span data-stu-id="25258-106">The period of time for which the the SAS URI generated by IoT Hub for file upload is valid.</span></span> <span data-ttu-id="25258-107">Finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-file-upload#file-upload-notification-configuration-options.</span><span class="sxs-lookup"><span data-stu-id="25258-107">See: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-file-upload#file-upload-notification-configuration-options.</span></span></param>
        <summary>
            <span data-ttu-id="25258-108">Initialisiert eine neue Instanz der StorageEndpointProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="25258-108">Initializes a new instance of the StorageEndpointProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionString">
      <MemberSignature Language="C#" Value="public string ConnectionString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConnectionString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.StorageEndpointProperties.ConnectionString" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionString As String" />
      <MemberSignature Language="F#" Value="member this.ConnectionString : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.StorageEndpointProperties.ConnectionString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="connectionString")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="25258-109">Ruft ab oder legt die Verbindungszeichenfolge für das Azure-Speicherkonto auf dem Dateien hochgeladen werden.</span><span class="sxs-lookup"><span data-stu-id="25258-109">Gets or sets the connection string for the Azure Storage account to which files are uploaded.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerName">
      <MemberSignature Language="C#" Value="public string ContainerName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContainerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.StorageEndpointProperties.ContainerName" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerName As String" />
      <MemberSignature Language="F#" Value="member this.ContainerName : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.StorageEndpointProperties.ContainerName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="containerName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="25258-110">Ruft ab oder legt den Namen des Stammcontainers fest, in dem Sie Dateien hochladen.</span><span class="sxs-lookup"><span data-stu-id="25258-110">Gets or sets the name of the root container where you upload files.</span></span>
            <span data-ttu-id="25258-111">Der Container muss nicht vorhanden, aber sollten erstellt mithilfe der "ConnectionString" angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="25258-111">The container need not exist but should be creatable using the connectionString specified.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SasTtlAsIso8601">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; SasTtlAsIso8601 { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; SasTtlAsIso8601" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.StorageEndpointProperties.SasTtlAsIso8601" />
      <MemberSignature Language="VB.NET" Value="Public Property SasTtlAsIso8601 As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.SasTtlAsIso8601 : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.StorageEndpointProperties.SasTtlAsIso8601" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sasTtlAsIso8601")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="25258-112">Ruft ab oder legt den Zeitraum für die die der SAS-URI generiert durch den IoT Hub Dateiupload ist ungültig.</span><span class="sxs-lookup"><span data-stu-id="25258-112">Gets or sets the period of time for which the the SAS URI generated by IoT Hub for file upload is valid.</span></span> <span data-ttu-id="25258-113">Finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-file-upload#file-upload-notification-configuration-options.</span><span class="sxs-lookup"><span data-stu-id="25258-113">See: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-file-upload#file-upload-notification-configuration-options.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.StorageEndpointProperties.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="storageEndpointProperties.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="25258-114">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="25258-114">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="25258-115">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="25258-115">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>