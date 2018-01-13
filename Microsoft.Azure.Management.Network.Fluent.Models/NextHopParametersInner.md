<Type Name="NextHopParametersInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner">
  <TypeSignature Language="C#" Value="public class NextHopParametersInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NextHopParametersInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner" />
  <TypeSignature Language="VB.NET" Value="Public Class NextHopParametersInner" />
  <TypeSignature Language="F#" Value="type NextHopParametersInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="67209-101">Parameter, die die Quelle und Ziel-Endpunkt zu definieren.</span><span class="sxs-lookup"><span data-stu-id="67209-101">Parameters that define the source and destination endpoint.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NextHopParametersInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="67209-102">Initialisiert eine neue Instanz der NextHopParametersInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="67209-102">Initializes a new instance of the NextHopParametersInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NextHopParametersInner (string targetResourceId, string sourceIPAddress, string destinationIPAddress, string targetNicResourceId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string targetResourceId, string sourceIPAddress, string destinationIPAddress, string targetNicResourceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (targetResourceId As String, sourceIPAddress As String, destinationIPAddress As String, Optional targetNicResourceId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner : string * string * string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner (targetResourceId, sourceIPAddress, destinationIPAddress, targetNicResourceId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="targetResourceId" Type="System.String" />
        <Parameter Name="sourceIPAddress" Type="System.String" />
        <Parameter Name="destinationIPAddress" Type="System.String" />
        <Parameter Name="targetNicResourceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="targetResourceId"><span data-ttu-id="67209-103">Der Ressourcenbezeichner der Zielressource für die ist die Aktion ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="67209-103">The resource identifier of the target resource against which the action is to be performed.</span></span></param>
        <param name="sourceIPAddress"><span data-ttu-id="67209-104">Die Quell-IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="67209-104">The source IP address.</span></span></param>
        <param name="destinationIPAddress"><span data-ttu-id="67209-105">Die Ziel-IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="67209-105">The destination IP address.</span></span></param>
        <param name="targetNicResourceId"><span data-ttu-id="67209-106">Der NIC-ID.</span><span class="sxs-lookup"><span data-stu-id="67209-106">The NIC ID.</span></span> <span data-ttu-id="67209-107">(Wenn der virtuelle Computer mehrere NICs hat und IP-Weiterleitung für ein beliebiges der Nics aktiviert ist, muss dann dieser Parameter angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="67209-107">(If VM has multiple NICs and IP forwarding is enabled on any of the nics, then this parameter must be specified.</span></span> <span data-ttu-id="67209-108">Andernfalls optional).</span><span class="sxs-lookup"><span data-stu-id="67209-108">Otherwise optional).</span></span></param>
        <summary>
            <span data-ttu-id="67209-109">Initialisiert eine neue Instanz der NextHopParametersInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="67209-109">Initializes a new instance of the NextHopParametersInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DestinationIPAddress">
      <MemberSignature Language="C#" Value="public string DestinationIPAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DestinationIPAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner.DestinationIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property DestinationIPAddress As String" />
      <MemberSignature Language="F#" Value="member this.DestinationIPAddress : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner.DestinationIPAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="destinationIPAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="67209-110">Ruft ab oder legt die IP-Zieladresse.</span><span class="sxs-lookup"><span data-stu-id="67209-110">Gets or sets the destination IP address.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceIPAddress">
      <MemberSignature Language="C#" Value="public string SourceIPAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceIPAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner.SourceIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceIPAddress As String" />
      <MemberSignature Language="F#" Value="member this.SourceIPAddress : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner.SourceIPAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceIPAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="67209-111">Ruft ab oder legt die Quell-IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="67209-111">Gets or sets the source IP address.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetNicResourceId">
      <MemberSignature Language="C#" Value="public string TargetNicResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetNicResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner.TargetNicResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetNicResourceId As String" />
      <MemberSignature Language="F#" Value="member this.TargetNicResourceId : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner.TargetNicResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetNicResourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="67209-112">Ruft ab oder legt die NIC ID.</span><span class="sxs-lookup"><span data-stu-id="67209-112">Gets or sets the NIC ID.</span></span> <span data-ttu-id="67209-113">(Wenn der virtuelle Computer mehrere NICs hat und IP-Weiterleitung für ein beliebiges der Nics aktiviert ist, muss dann dieser Parameter angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="67209-113">(If VM has multiple NICs and IP forwarding is enabled on any of the nics, then this parameter must be specified.</span></span> <span data-ttu-id="67209-114">Andernfalls optional).</span><span class="sxs-lookup"><span data-stu-id="67209-114">Otherwise optional).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetResourceId">
      <MemberSignature Language="C#" Value="public string TargetResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner.TargetResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetResourceId As String" />
      <MemberSignature Language="F#" Value="member this.TargetResourceId : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner.TargetResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetResourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="67209-115">Abrufen oder festlegen den Ressourcenbezeichner der Zielressource für die ist die Aktion ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="67209-115">Gets or sets the resource identifier of the target resource against which the action is to be performed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.NextHopParametersInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="nextHopParametersInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="67209-116">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="67209-116">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="67209-117">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="67209-117">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>