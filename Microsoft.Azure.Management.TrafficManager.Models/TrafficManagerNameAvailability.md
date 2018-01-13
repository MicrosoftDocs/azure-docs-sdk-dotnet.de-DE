<Type Name="TrafficManagerNameAvailability" FullName="Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerNameAvailability">
  <TypeSignature Language="C#" Value="public class TrafficManagerNameAvailability" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TrafficManagerNameAvailability extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerNameAvailability" />
  <TypeSignature Language="VB.NET" Value="Public Class TrafficManagerNameAvailability" />
  <TypeSignature Language="F#" Value="type TrafficManagerNameAvailability = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d0d8e-101">Klasse, die eine Verfügbarkeit eines Traffic Manager-Antwort darstellt.</span><span class="sxs-lookup"><span data-stu-id="d0d8e-101">Class representing a Traffic Manager Name Availability response.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TrafficManagerNameAvailability ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerNameAvailability.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d0d8e-102">Initialisiert eine neue Instanz der TrafficManagerNameAvailability-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d0d8e-102">Initializes a new instance of the TrafficManagerNameAvailability class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TrafficManagerNameAvailability (string name = null, string type = null, Nullable&lt;bool&gt; nameAvailable = null, string reason = null, string message = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string type, valuetype System.Nullable`1&lt;bool&gt; nameAvailable, string reason, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerNameAvailability.#ctor(System.String,System.String,System.Nullable{System.Boolean},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional type As String = null, Optional nameAvailable As Nullable(Of Boolean) = null, Optional reason As String = null, Optional message As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerNameAvailability : string * string * Nullable&lt;bool&gt; * string * string -&gt; Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerNameAvailability" Usage="new Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerNameAvailability (name, type, nameAvailable, reason, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="nameAvailable" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="reason" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="d0d8e-103">Der relative Dateiname.</span><span class="sxs-lookup"><span data-stu-id="d0d8e-103">The relative name.</span></span></param>
        <param name="type"><span data-ttu-id="d0d8e-104">Traffic Manager-Profil Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="d0d8e-104">Traffic Manager profile resource type.</span></span></param>
        <param name="nameAvailable"><span data-ttu-id="d0d8e-105">Beschreibt, ob der relative Name verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="d0d8e-105">Describes whether the relative name is available or not.</span></span></param>
        <param name="reason"><span data-ttu-id="d0d8e-106">Der Grund, warum der Name nicht verfügbar, wenn zutreffend ist.</span><span class="sxs-lookup"><span data-stu-id="d0d8e-106">The reason why the name is not available, when applicable.</span></span></param>
        <param name="message"><span data-ttu-id="d0d8e-107">Eine beschreibende Meldung, die erklärt, warum der Name nicht verfügbar, wenn zutreffend ist.</span><span class="sxs-lookup"><span data-stu-id="d0d8e-107">Descriptive message that explains why the name is not available, when applicable.</span></span></param>
        <summary>
            <span data-ttu-id="d0d8e-108">Initialisiert eine neue Instanz der TrafficManagerNameAvailability-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d0d8e-108">Initializes a new instance of the TrafficManagerNameAvailability class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerNameAvailability.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerNameAvailability.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="d0d8e-109">Ruft ab, oder legt ihn fest beschreibenden Meldung an, die erklärt, warum der Name nicht verfügbar, wenn zutreffend ist.</span><span class="sxs-lookup"><span data-stu-id="d0d8e-109">Gets or sets descriptive message that explains why the name is not available, when applicable.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerNameAvailability.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerNameAvailability.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d0d8e-110">Ruft ab oder legt den relativen Namen fest.</span><span class="sxs-lookup"><span data-stu-id="d0d8e-110">Gets or sets the relative name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NameAvailable">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; NameAvailable { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; NameAvailable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerNameAvailability.NameAvailable" />
      <MemberSignature Language="VB.NET" Value="Public Property NameAvailable As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.NameAvailable : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerNameAvailability.NameAvailable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="d0d8e-111">Beschreibt, ruft ab oder legt sie fest, ob der relative Name verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="d0d8e-111">Gets or sets describes whether the relative name is available or not.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reason">
      <MemberSignature Language="C#" Value="public string Reason { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Reason" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerNameAvailability.Reason" />
      <MemberSignature Language="VB.NET" Value="Public Property Reason As String" />
      <MemberSignature Language="F#" Value="member this.Reason : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerNameAvailability.Reason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="reason")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d0d8e-112">Ruft ab oder legt den Grund, warum der Name nicht verfügbar, wenn zutreffend ist.</span><span class="sxs-lookup"><span data-stu-id="d0d8e-112">Gets or sets the reason why the name is not available, when applicable.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerNameAvailability.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerNameAvailability.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d0d8e-113">Ruft ab, oder legt ihn fest Traffic Manager-Profil Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="d0d8e-113">Gets or sets traffic Manager profile resource type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>