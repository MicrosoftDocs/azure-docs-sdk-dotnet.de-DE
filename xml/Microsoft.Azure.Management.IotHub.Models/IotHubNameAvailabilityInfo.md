<Type Name="IotHubNameAvailabilityInfo" FullName="Microsoft.Azure.Management.IotHub.Models.IotHubNameAvailabilityInfo">
  <TypeSignature Language="C#" Value="public class IotHubNameAvailabilityInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IotHubNameAvailabilityInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.Models.IotHubNameAvailabilityInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class IotHubNameAvailabilityInfo" />
  <TypeSignature Language="F#" Value="type IotHubNameAvailabilityInfo = class" />
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
            <span data-ttu-id="389ef-101">Die Eigenschaften, der angibt, ob eine bestimmte IoT Hub-Name verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="389ef-101">The properties indicating whether a given IoT hub name is available.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IotHubNameAvailabilityInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.IotHubNameAvailabilityInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="389ef-102">Initialisiert eine neue Instanz der IotHubNameAvailabilityInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="389ef-102">Initializes a new instance of the IotHubNameAvailabilityInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IotHubNameAvailabilityInfo (Nullable&lt;bool&gt; nameAvailable = null, Nullable&lt;Microsoft.Azure.Management.IotHub.Models.IotHubNameUnavailabilityReason&gt; reason = null, string message = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; nameAvailable, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.IotHub.Models.IotHubNameUnavailabilityReason&gt; reason, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.IotHubNameAvailabilityInfo.#ctor(System.Nullable{System.Boolean},System.Nullable{Microsoft.Azure.Management.IotHub.Models.IotHubNameUnavailabilityReason},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional nameAvailable As Nullable(Of Boolean) = null, Optional reason As Nullable(Of IotHubNameUnavailabilityReason) = null, Optional message As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.IotHub.Models.IotHubNameAvailabilityInfo : Nullable&lt;bool&gt; * Nullable&lt;Microsoft.Azure.Management.IotHub.Models.IotHubNameUnavailabilityReason&gt; * string -&gt; Microsoft.Azure.Management.IotHub.Models.IotHubNameAvailabilityInfo" Usage="new Microsoft.Azure.Management.IotHub.Models.IotHubNameAvailabilityInfo (nameAvailable, reason, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nameAvailable" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="reason" Type="System.Nullable&lt;Microsoft.Azure.Management.IotHub.Models.IotHubNameUnavailabilityReason&gt;" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nameAvailable"><span data-ttu-id="389ef-103">Der Wert, der angibt, ob der angegebene Name verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="389ef-103">The value which indicates whether the provided name is available.</span></span></param>
        <param name="reason"><span data-ttu-id="389ef-104">Der Grund nicht verfügbar sind.</span><span class="sxs-lookup"><span data-stu-id="389ef-104">The reason for unavailability.</span></span> <span data-ttu-id="389ef-105">Folgende Werte sind möglich: "Ungültig", "AlreadyExists"</span><span class="sxs-lookup"><span data-stu-id="389ef-105">Possible values include: 'Invalid', 'AlreadyExists'</span></span></param>
        <param name="message"><span data-ttu-id="389ef-106">Die detaillierte Grund-Meldung.</span><span class="sxs-lookup"><span data-stu-id="389ef-106">The detailed reason message.</span></span></param>
        <summary>
            <span data-ttu-id="389ef-107">Initialisiert eine neue Instanz der IotHubNameAvailabilityInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="389ef-107">Initializes a new instance of the IotHubNameAvailabilityInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.IotHubNameAvailabilityInfo.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.IotHubNameAvailabilityInfo.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="389ef-108">Ermittelt oder definiert die detaillierte Grund-Nachricht.</span><span class="sxs-lookup"><span data-stu-id="389ef-108">Gets or sets the detailed reason message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NameAvailable">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; NameAvailable { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; NameAvailable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.IotHubNameAvailabilityInfo.NameAvailable" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NameAvailable As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.NameAvailable : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.IotHub.Models.IotHubNameAvailabilityInfo.NameAvailable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nameAvailable")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="389ef-109">Ruft den Wert, der angibt, ob der angegebene Name verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="389ef-109">Gets the value which indicates whether the provided name is available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reason">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.IotHub.Models.IotHubNameUnavailabilityReason&gt; Reason { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.IotHub.Models.IotHubNameUnavailabilityReason&gt; Reason" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.IotHubNameAvailabilityInfo.Reason" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Reason As Nullable(Of IotHubNameUnavailabilityReason)" />
      <MemberSignature Language="F#" Value="member this.Reason : Nullable&lt;Microsoft.Azure.Management.IotHub.Models.IotHubNameUnavailabilityReason&gt;" Usage="Microsoft.Azure.Management.IotHub.Models.IotHubNameAvailabilityInfo.Reason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="reason")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.IotHub.Models.IotHubNameUnavailabilityReason&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="389ef-110">Ruft den Grund nicht verfügbar sind.</span><span class="sxs-lookup"><span data-stu-id="389ef-110">Gets the reason for unavailability.</span></span> <span data-ttu-id="389ef-111">Folgende Werte sind möglich: "Ungültig", "AlreadyExists"</span><span class="sxs-lookup"><span data-stu-id="389ef-111">Possible values include: 'Invalid', 'AlreadyExists'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>