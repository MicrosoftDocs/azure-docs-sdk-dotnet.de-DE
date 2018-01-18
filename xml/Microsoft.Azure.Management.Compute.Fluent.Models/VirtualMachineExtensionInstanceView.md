<Type Name="VirtualMachineExtensionInstanceView" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInstanceView">
  <TypeSignature Language="C#" Value="public class VirtualMachineExtensionInstanceView" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineExtensionInstanceView extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInstanceView" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineExtensionInstanceView" />
  <TypeSignature Language="F#" Value="type VirtualMachineExtensionInstanceView = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="23f7a-101">Die Instanzansicht der Erweiterung eines virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="23f7a-101">The instance view of a virtual machine extension.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineExtensionInstanceView ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInstanceView.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="23f7a-102">Initialisiert eine neue Instanz der VirtualMachineExtensionInstanceView-Klasse.</span><span class="sxs-lookup"><span data-stu-id="23f7a-102">Initializes a new instance of the VirtualMachineExtensionInstanceView class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineExtensionInstanceView (string name = null, string type = null, string typeHandlerVersion = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus&gt; substatuses = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus&gt; statuses = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string type, string typeHandlerVersion, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus&gt; substatuses, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus&gt; statuses) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInstanceView.#ctor(System.String,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus},System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional type As String = null, Optional typeHandlerVersion As String = null, Optional substatuses As IList(Of InstanceViewStatus) = null, Optional statuses As IList(Of InstanceViewStatus) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInstanceView : string * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInstanceView" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInstanceView (name, type, typeHandlerVersion, substatuses, statuses)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="typeHandlerVersion" Type="System.String" />
        <Parameter Name="substatuses" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus&gt;" />
        <Parameter Name="statuses" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="23f7a-103">Der Name des virtuellen Computers Erweiterung.</span><span class="sxs-lookup"><span data-stu-id="23f7a-103">The virtual machine extension name.</span></span></param>
        <param name="type"><span data-ttu-id="23f7a-104">Der vollständige Typ des erweiterungshandlers dem Verleger und Typ enthält.</span><span class="sxs-lookup"><span data-stu-id="23f7a-104">The full type of the extension handler which includes both publisher and type.</span></span></param>
        <param name="typeHandlerVersion"><span data-ttu-id="23f7a-105">Die Version des erweiterungshandlers.</span><span class="sxs-lookup"><span data-stu-id="23f7a-105">The type version of the extension handler.</span></span></param>
        <param name="substatuses"><span data-ttu-id="23f7a-106">Die Statusinformationen für die Ressource.</span><span class="sxs-lookup"><span data-stu-id="23f7a-106">The resource status information.</span></span></param>
        <param name="statuses"><span data-ttu-id="23f7a-107">Die Statusinformationen für die Ressource.</span><span class="sxs-lookup"><span data-stu-id="23f7a-107">The resource status information.</span></span></param>
        <summary>
            <span data-ttu-id="23f7a-108">Initialisiert eine neue Instanz der VirtualMachineExtensionInstanceView-Klasse.</span><span class="sxs-lookup"><span data-stu-id="23f7a-108">Initializes a new instance of the VirtualMachineExtensionInstanceView class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInstanceView.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInstanceView.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="23f7a-109">Ruft ab oder legt den Namen des virtuellen Computers-Erweiterung.</span><span class="sxs-lookup"><span data-stu-id="23f7a-109">Gets or sets the virtual machine extension name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Statuses">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus&gt; Statuses { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus&gt; Statuses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInstanceView.Statuses" />
      <MemberSignature Language="VB.NET" Value="Public Property Statuses As IList(Of InstanceViewStatus)" />
      <MemberSignature Language="F#" Value="member this.Statuses : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInstanceView.Statuses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="statuses")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="23f7a-110">Ruft ab oder legt die Statusinformationen für die Ressource.</span><span class="sxs-lookup"><span data-stu-id="23f7a-110">Gets or sets the resource status information.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Substatuses">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus&gt; Substatuses { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus&gt; Substatuses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInstanceView.Substatuses" />
      <MemberSignature Language="VB.NET" Value="Public Property Substatuses As IList(Of InstanceViewStatus)" />
      <MemberSignature Language="F#" Value="member this.Substatuses : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInstanceView.Substatuses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="substatuses")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="23f7a-111">Ruft ab oder legt die Statusinformationen für die Ressource.</span><span class="sxs-lookup"><span data-stu-id="23f7a-111">Gets or sets the resource status information.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInstanceView.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInstanceView.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="23f7a-112">Ruft ab, oder legt ihn fest die vollständige anwendungserweiterungs-Handler, der Verleger und Typ enthält.</span><span class="sxs-lookup"><span data-stu-id="23f7a-112">Gets or sets the full type of the extension handler which includes both publisher and type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TypeHandlerVersion">
      <MemberSignature Language="C#" Value="public string TypeHandlerVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TypeHandlerVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInstanceView.TypeHandlerVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property TypeHandlerVersion As String" />
      <MemberSignature Language="F#" Value="member this.TypeHandlerVersion : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionInstanceView.TypeHandlerVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="23f7a-113">Ruft ab oder legt die Version des erweiterungshandlers.</span><span class="sxs-lookup"><span data-stu-id="23f7a-113">Gets or sets the type version of the extension handler.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>