<Type Name="FallbackRouteProperties" FullName="Microsoft.Azure.Management.IotHub.Models.FallbackRouteProperties">
  <TypeSignature Language="C#" Value="public class FallbackRouteProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi FallbackRouteProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.Models.FallbackRouteProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class FallbackRouteProperties" />
  <TypeSignature Language="F#" Value="type FallbackRouteProperties = class" />
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
            <span data-ttu-id="3e4b3-101">Die Eigenschaften der fallback Route.</span><span class="sxs-lookup"><span data-stu-id="3e4b3-101">The properties of the fallback route.</span></span> <span data-ttu-id="3e4b3-102">IoT Hub verwendet diese Eigenschaften auf, wenn sie Nachrichten an den alternativen Endpunkt weiterleitet.</span><span class="sxs-lookup"><span data-stu-id="3e4b3-102">IoT Hub uses these properties when it routes messages to the fallback endpoint.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FallbackRouteProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.FallbackRouteProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3e4b3-103">Initialisiert eine neue Instanz der FallbackRouteProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3e4b3-103">Initializes a new instance of the FallbackRouteProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FallbackRouteProperties (System.Collections.Generic.IList&lt;string&gt; endpointNames, bool isEnabled, string condition = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;string&gt; endpointNames, bool isEnabled, string condition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.FallbackRouteProperties.#ctor(System.Collections.Generic.IList{System.String},System.Boolean,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (endpointNames As IList(Of String), isEnabled As Boolean, Optional condition As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.IotHub.Models.FallbackRouteProperties : System.Collections.Generic.IList&lt;string&gt; * bool * string -&gt; Microsoft.Azure.Management.IotHub.Models.FallbackRouteProperties" Usage="new Microsoft.Azure.Management.IotHub.Models.FallbackRouteProperties (endpointNames, isEnabled, condition)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="endpointNames" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="isEnabled" Type="System.Boolean" />
        <Parameter Name="condition" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="endpointNames"><span data-ttu-id="3e4b3-104">Die Liste der Endpunkte, die Nachrichten, die die Bedingung erfüllen, weitergeleitet werden.</span><span class="sxs-lookup"><span data-stu-id="3e4b3-104">The list of endpoints to which the messages that satisfy the condition are routed to.</span></span> <span data-ttu-id="3e4b3-105">Derzeit wird nur 1 Endpunkt zulässig.</span><span class="sxs-lookup"><span data-stu-id="3e4b3-105">Currently only 1 endpoint is allowed.</span></span></param>
        <param name="isEnabled"><span data-ttu-id="3e4b3-106">Dient zum angeben, ob die Route fallback aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="3e4b3-106">Used to specify whether the fallback route is enabled.</span></span></param>
        <param name="condition"><span data-ttu-id="3e4b3-107">Die Bedingung, die ausgewertet wird, um die fallback Route anzuwenden.</span><span class="sxs-lookup"><span data-stu-id="3e4b3-107">The condition which is evaluated in order to apply the fallback route.</span></span> <span data-ttu-id="3e4b3-108">Wenn die Bedingung nicht, dass er auf "true" ausgewertet wird standardmäßig angegeben ist.</span><span class="sxs-lookup"><span data-stu-id="3e4b3-108">If the condition is not provided it will evaluate to true by default.</span></span> <span data-ttu-id="3e4b3-109">Grammatik, finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-query-language</span><span class="sxs-lookup"><span data-stu-id="3e4b3-109">For grammar, See: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-query-language</span></span></param>
        <summary>
            <span data-ttu-id="3e4b3-110">Initialisiert eine neue Instanz der FallbackRouteProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3e4b3-110">Initializes a new instance of the FallbackRouteProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Condition">
      <MemberSignature Language="C#" Value="public string Condition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Condition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.FallbackRouteProperties.Condition" />
      <MemberSignature Language="VB.NET" Value="Public Property Condition As String" />
      <MemberSignature Language="F#" Value="member this.Condition : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.FallbackRouteProperties.Condition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="condition")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e4b3-111">Ruft ab oder legt die Bedingung, die ausgewertet wird, um die fallback Route anzuwenden.</span><span class="sxs-lookup"><span data-stu-id="3e4b3-111">Gets or sets the condition which is evaluated in order to apply the fallback route.</span></span> <span data-ttu-id="3e4b3-112">Wenn die Bedingung nicht, dass er auf "true" ausgewertet wird standardmäßig angegeben ist.</span><span class="sxs-lookup"><span data-stu-id="3e4b3-112">If the condition is not provided it will evaluate to true by default.</span></span> <span data-ttu-id="3e4b3-113">Grammatik, finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-query-language</span><span class="sxs-lookup"><span data-stu-id="3e4b3-113">For grammar, See: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-query-language</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndpointNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; EndpointNames { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; EndpointNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.FallbackRouteProperties.EndpointNames" />
      <MemberSignature Language="VB.NET" Value="Public Property EndpointNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.EndpointNames : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.FallbackRouteProperties.EndpointNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endpointNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e4b3-114">Ruft ab oder legt die Liste der Endpunkte, die Nachrichten, die die Bedingung erfüllen, weitergeleitet werden.</span><span class="sxs-lookup"><span data-stu-id="3e4b3-114">Gets or sets the list of endpoints to which the messages that satisfy the condition are routed to.</span></span> <span data-ttu-id="3e4b3-115">Derzeit wird nur 1 Endpunkt zulässig.</span><span class="sxs-lookup"><span data-stu-id="3e4b3-115">Currently only 1 endpoint is allowed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsEnabled">
      <MemberSignature Language="C#" Value="public bool IsEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.FallbackRouteProperties.IsEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property IsEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsEnabled : bool with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.FallbackRouteProperties.IsEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e4b3-116">Ruft ab oder legt ihn fest, die verwendet, um anzugeben, ob die Route fallback aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="3e4b3-116">Gets or sets used to specify whether the fallback route is enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Source">
      <MemberSignature Language="C#" Value="public static string Source { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string Source" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.FallbackRouteProperties.Source" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property Source As String" />
      <MemberSignature Language="F#" Value="member this.Source : string" Usage="Microsoft.Azure.Management.IotHub.Models.FallbackRouteProperties.Source" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="source")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e4b3-117">Die Quelle für die die Weiterleitungsregel auf angewendet wird.</span><span class="sxs-lookup"><span data-stu-id="3e4b3-117">The source to which the routing rule is to be applied to.</span></span> <span data-ttu-id="3e4b3-118">Beispielsweise DeviceMessages</span><span class="sxs-lookup"><span data-stu-id="3e4b3-118">For example, DeviceMessages</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.FallbackRouteProperties.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="fallbackRouteProperties.Validate " />
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
            <span data-ttu-id="3e4b3-119">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="3e4b3-119">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="3e4b3-120">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="3e4b3-120">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>