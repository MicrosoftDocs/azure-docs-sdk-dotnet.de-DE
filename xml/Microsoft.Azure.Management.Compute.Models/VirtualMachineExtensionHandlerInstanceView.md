<Type Name="VirtualMachineExtensionHandlerInstanceView" FullName="Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionHandlerInstanceView">
  <TypeSignature Language="C#" Value="public class VirtualMachineExtensionHandlerInstanceView" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineExtensionHandlerInstanceView extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionHandlerInstanceView" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineExtensionHandlerInstanceView" />
  <TypeSignature Language="F#" Value="type VirtualMachineExtensionHandlerInstanceView = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0d813-101">Die Instanzansicht von einem VM-Erweiterungshandler.</span><span class="sxs-lookup"><span data-stu-id="0d813-101">The instance view of a virtual machine extension handler.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineExtensionHandlerInstanceView ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionHandlerInstanceView.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0d813-102">Initialisiert eine neue Instanz der VirtualMachineExtensionHandlerInstanceView-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0d813-102">Initializes a new instance of the VirtualMachineExtensionHandlerInstanceView class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineExtensionHandlerInstanceView (string type = null, string typeHandlerVersion = null, Microsoft.Azure.Management.Compute.Models.InstanceViewStatus status = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string type, string typeHandlerVersion, class Microsoft.Azure.Management.Compute.Models.InstanceViewStatus status) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionHandlerInstanceView.#ctor(System.String,System.String,Microsoft.Azure.Management.Compute.Models.InstanceViewStatus)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional type As String = null, Optional typeHandlerVersion As String = null, Optional status As InstanceViewStatus = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionHandlerInstanceView : string * string * Microsoft.Azure.Management.Compute.Models.InstanceViewStatus -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionHandlerInstanceView" Usage="new Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionHandlerInstanceView (type, typeHandlerVersion, status)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="typeHandlerVersion" Type="System.String" />
        <Parameter Name="status" Type="Microsoft.Azure.Management.Compute.Models.InstanceViewStatus" />
      </Parameters>
      <Docs>
        <param name="type"><span data-ttu-id="0d813-103">Gibt den Typ der Erweiterung an. Ein Beispiel ist "CustomScriptExtension".</span><span class="sxs-lookup"><span data-stu-id="0d813-103">Specifies the type of the extension; an example is "CustomScriptExtension".</span></span></param>
        <param name="typeHandlerVersion"><span data-ttu-id="0d813-104">Gibt die Version des Skript-Handlers.</span><span class="sxs-lookup"><span data-stu-id="0d813-104">Specifies the version of the script handler.</span></span></param>
        <param name="status"><span data-ttu-id="0d813-105">Den Erweiterungsstatus Handler.</span><span class="sxs-lookup"><span data-stu-id="0d813-105">The extension handler status.</span></span></param>
        <summary>
            <span data-ttu-id="0d813-106">Initialisiert eine neue Instanz der VirtualMachineExtensionHandlerInstanceView-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0d813-106">Initializes a new instance of the VirtualMachineExtensionHandlerInstanceView class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.InstanceViewStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.InstanceViewStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionHandlerInstanceView.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As InstanceViewStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.Management.Compute.Models.InstanceViewStatus with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionHandlerInstanceView.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.InstanceViewStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0d813-107">Ruft ab oder legt den Handler Erweiterungsstatus.</span><span class="sxs-lookup"><span data-stu-id="0d813-107">Gets or sets the extension handler status.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionHandlerInstanceView.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionHandlerInstanceView.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="0d813-108">Ruft ab oder legt gibt den Typ der Erweiterung an. Ein Beispiel ist "CustomScriptExtension".</span><span class="sxs-lookup"><span data-stu-id="0d813-108">Gets or sets specifies the type of the extension; an example is "CustomScriptExtension".</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TypeHandlerVersion">
      <MemberSignature Language="C#" Value="public string TypeHandlerVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TypeHandlerVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionHandlerInstanceView.TypeHandlerVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property TypeHandlerVersion As String" />
      <MemberSignature Language="F#" Value="member this.TypeHandlerVersion : string with get, set" Usage="Microsoft.Azure.Management.Compute.Models.VirtualMachineExtensionHandlerInstanceView.TypeHandlerVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeHandlerVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0d813-109">Ruft ab oder legt gibt die Version des Handlers Skript an.</span><span class="sxs-lookup"><span data-stu-id="0d813-109">Gets or sets specifies the version of the script handler.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>