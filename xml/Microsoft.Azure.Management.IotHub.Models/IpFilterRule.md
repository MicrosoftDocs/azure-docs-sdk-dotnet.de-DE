<Type Name="IpFilterRule" FullName="Microsoft.Azure.Management.IotHub.Models.IpFilterRule">
  <TypeSignature Language="C#" Value="public class IpFilterRule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IpFilterRule extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.Models.IpFilterRule" />
  <TypeSignature Language="VB.NET" Value="Public Class IpFilterRule" />
  <TypeSignature Language="F#" Value="type IpFilterRule = class" />
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
            <span data-ttu-id="98870-101">Die IP-Filter-Regeln für den IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="98870-101">The IP filter rules for the IoT hub.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IpFilterRule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.IpFilterRule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="98870-102">Initialisiert eine neue Instanz der IpFilterRule-Klasse.</span><span class="sxs-lookup"><span data-stu-id="98870-102">Initializes a new instance of the IpFilterRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IpFilterRule (string filterName, Microsoft.Azure.Management.IotHub.Models.IpFilterActionType action, string ipMask);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string filterName, valuetype Microsoft.Azure.Management.IotHub.Models.IpFilterActionType action, string ipMask) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.IpFilterRule.#ctor(System.String,Microsoft.Azure.Management.IotHub.Models.IpFilterActionType,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (filterName As String, action As IpFilterActionType, ipMask As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.IotHub.Models.IpFilterRule : string * Microsoft.Azure.Management.IotHub.Models.IpFilterActionType * string -&gt; Microsoft.Azure.Management.IotHub.Models.IpFilterRule" Usage="new Microsoft.Azure.Management.IotHub.Models.IpFilterRule (filterName, action, ipMask)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="filterName" Type="System.String" />
        <Parameter Name="action" Type="Microsoft.Azure.Management.IotHub.Models.IpFilterActionType" />
        <Parameter Name="ipMask" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="filterName"><span data-ttu-id="98870-103">Der Name der IP-Filterregel.</span><span class="sxs-lookup"><span data-stu-id="98870-103">The name of the IP filter rule.</span></span></param>
        <param name="action"><span data-ttu-id="98870-104">Die gewünschte Aktion für Anforderungen, die durch diese Regel erfasst.</span><span class="sxs-lookup"><span data-stu-id="98870-104">The desired action for requests captured by this rule.</span></span> <span data-ttu-id="98870-105">Folgende Werte sind möglich: "Akzeptiert", "Ablehnen"</span><span class="sxs-lookup"><span data-stu-id="98870-105">Possible values include: 'Accept', 'Reject'</span></span></param>
        <param name="ipMask"><span data-ttu-id="98870-106">Eine Zeichenfolge, die IP-Adressbereich in CIDR-Notation für die Regel enthält.</span><span class="sxs-lookup"><span data-stu-id="98870-106">A string that contains the IP address range in CIDR notation for the rule.</span></span></param>
        <summary>
            <span data-ttu-id="98870-107">Initialisiert eine neue Instanz der IpFilterRule-Klasse.</span><span class="sxs-lookup"><span data-stu-id="98870-107">Initializes a new instance of the IpFilterRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Action">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.IotHub.Models.IpFilterActionType Action { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.IotHub.Models.IpFilterActionType Action" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.IpFilterRule.Action" />
      <MemberSignature Language="VB.NET" Value="Public Property Action As IpFilterActionType" />
      <MemberSignature Language="F#" Value="member this.Action : Microsoft.Azure.Management.IotHub.Models.IpFilterActionType with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.IpFilterRule.Action" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="action")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.IpFilterActionType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98870-108">Ruft ab oder legt fest, die gewünschte Aktion für Anforderungen, die durch diese Regel erfasst.</span><span class="sxs-lookup"><span data-stu-id="98870-108">Gets or sets the desired action for requests captured by this rule.</span></span>
            <span data-ttu-id="98870-109">Folgende Werte sind möglich: "Akzeptiert", "Ablehnen"</span><span class="sxs-lookup"><span data-stu-id="98870-109">Possible values include: 'Accept', 'Reject'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FilterName">
      <MemberSignature Language="C#" Value="public string FilterName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FilterName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.IpFilterRule.FilterName" />
      <MemberSignature Language="VB.NET" Value="Public Property FilterName As String" />
      <MemberSignature Language="F#" Value="member this.FilterName : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.IpFilterRule.FilterName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="filterName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98870-110">Ruft ab oder legt den Namen der IP-Filterregel fest.</span><span class="sxs-lookup"><span data-stu-id="98870-110">Gets or sets the name of the IP filter rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IpMask">
      <MemberSignature Language="C#" Value="public string IpMask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IpMask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.IpFilterRule.IpMask" />
      <MemberSignature Language="VB.NET" Value="Public Property IpMask As String" />
      <MemberSignature Language="F#" Value="member this.IpMask : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.IpFilterRule.IpMask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ipMask")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98870-111">Ruft ab oder legt eine Zeichenfolge, die IP-Adressbereich in CIDR-Notation für die Regel enthält.</span><span class="sxs-lookup"><span data-stu-id="98870-111">Gets or sets a string that contains the IP address range in CIDR notation for the rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.IpFilterRule.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="ipFilterRule.Validate " />
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
            <span data-ttu-id="98870-112">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="98870-112">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="98870-113">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="98870-113">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>