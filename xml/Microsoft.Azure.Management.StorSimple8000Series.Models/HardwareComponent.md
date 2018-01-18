<Type Name="HardwareComponent" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponent">
  <TypeSignature Language="C#" Value="public class HardwareComponent" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HardwareComponent extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponent" />
  <TypeSignature Language="VB.NET" Value="Public Class HardwareComponent" />
  <TypeSignature Language="F#" Value="type HardwareComponent = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f46e3-101">Die betreffende Hardwarekomponente.</span><span class="sxs-lookup"><span data-stu-id="f46e3-101">The hardware component.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HardwareComponent ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponent.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f46e3-102">Initialisiert eine neue Instanz der HardwareComponent-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f46e3-102">Initializes a new instance of the HardwareComponent class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HardwareComponent (string componentId, string displayName, Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponentStatus status, string statusDisplayName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string componentId, string displayName, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponentStatus status, string statusDisplayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponent.#ctor(System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponentStatus,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (componentId As String, displayName As String, status As HardwareComponentStatus, statusDisplayName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponent : string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponentStatus * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponent" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponent (componentId, displayName, status, statusDisplayName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="componentId" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="status" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponentStatus" />
        <Parameter Name="statusDisplayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="componentId"><span data-ttu-id="f46e3-103">Die Komponente-ID.</span><span class="sxs-lookup"><span data-stu-id="f46e3-103">The component ID.</span></span></param>
        <param name="displayName"><span data-ttu-id="f46e3-104">Der Anzeigename der Hardware-Komponente.</span><span class="sxs-lookup"><span data-stu-id="f46e3-104">The display name of the hardware component.</span></span></param>
        <param name="status"><span data-ttu-id="f46e3-105">Der Status der Hardware-Komponente.</span><span class="sxs-lookup"><span data-stu-id="f46e3-105">The status of the hardware component.</span></span> <span data-ttu-id="f46e3-106">Folgende Werte sind möglich: 'Unbekannt', 'NotPresent', 'PoweredOff', 'Ok', 'Wiederherstellen', 'Warnung', 'Fehler'</span><span class="sxs-lookup"><span data-stu-id="f46e3-106">Possible values include: 'Unknown', 'NotPresent', 'PoweredOff', 'Ok', 'Recovering', 'Warning', 'Failure'</span></span></param>
        <param name="statusDisplayName"><span data-ttu-id="f46e3-107">Der Anzeigename des Status der Hardwarekomponente.</span><span class="sxs-lookup"><span data-stu-id="f46e3-107">The display name of the status of hardware component.</span></span></param>
        <summary>
            <span data-ttu-id="f46e3-108">Initialisiert eine neue Instanz der HardwareComponent-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f46e3-108">Initializes a new instance of the HardwareComponent class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComponentId">
      <MemberSignature Language="C#" Value="public string ComponentId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ComponentId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponent.ComponentId" />
      <MemberSignature Language="VB.NET" Value="Public Property ComponentId As String" />
      <MemberSignature Language="F#" Value="member this.ComponentId : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponent.ComponentId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="componentId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f46e3-109">Ruft ab oder legt die ID der Komponente fest.</span><span class="sxs-lookup"><span data-stu-id="f46e3-109">Gets or sets the component ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponent.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponent.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f46e3-110">Ruft ab oder legt den Anzeigenamen der Hardware-Komponente.</span><span class="sxs-lookup"><span data-stu-id="f46e3-110">Gets or sets the display name of the hardware component.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponentStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponentStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponent.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As HardwareComponentStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponentStatus with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponent.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponentStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f46e3-111">Ruft ab oder legt den Status der Hardware-Komponente fest.</span><span class="sxs-lookup"><span data-stu-id="f46e3-111">Gets or sets the status of the hardware component.</span></span> <span data-ttu-id="f46e3-112">Folgende Werte sind möglich: 'Unbekannt', 'NotPresent', 'PoweredOff', 'Ok', 'Wiederherstellen', 'Warnung', 'Fehler'</span><span class="sxs-lookup"><span data-stu-id="f46e3-112">Possible values include: 'Unknown', 'NotPresent', 'PoweredOff', 'Ok', 'Recovering', 'Warning', 'Failure'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusDisplayName">
      <MemberSignature Language="C#" Value="public string StatusDisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StatusDisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponent.StatusDisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property StatusDisplayName As String" />
      <MemberSignature Language="F#" Value="member this.StatusDisplayName : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponent.StatusDisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="statusDisplayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f46e3-113">Ruft ab oder legt den Anzeigenamen des Status der Hardwarekomponente.</span><span class="sxs-lookup"><span data-stu-id="f46e3-113">Gets or sets the display name of the status of hardware component.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponent.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="hardwareComponent.Validate " />
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
            <span data-ttu-id="f46e3-114">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="f46e3-114">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f46e3-115">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="f46e3-115">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>