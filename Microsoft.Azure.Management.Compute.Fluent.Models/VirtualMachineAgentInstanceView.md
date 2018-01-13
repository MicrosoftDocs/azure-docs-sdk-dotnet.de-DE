<Type Name="VirtualMachineAgentInstanceView" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineAgentInstanceView">
  <TypeSignature Language="C#" Value="public class VirtualMachineAgentInstanceView" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineAgentInstanceView extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineAgentInstanceView" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineAgentInstanceView" />
  <TypeSignature Language="F#" Value="type VirtualMachineAgentInstanceView = class" />
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
            Die Instanzansicht eines der VM-Agent auf dem virtuellen Computer ausgeführt werden soll.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineAgentInstanceView ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineAgentInstanceView.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der VirtualMachineAgentInstanceView-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineAgentInstanceView (string vmAgentVersion = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionHandlerInstanceView&gt; extensionHandlers = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus&gt; statuses = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string vmAgentVersion, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionHandlerInstanceView&gt; extensionHandlers, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus&gt; statuses) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineAgentInstanceView.#ctor(System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionHandlerInstanceView},System.Collections.Generic.IList{Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional vmAgentVersion As String = null, Optional extensionHandlers As IList(Of VirtualMachineExtensionHandlerInstanceView) = null, Optional statuses As IList(Of InstanceViewStatus) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineAgentInstanceView : string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionHandlerInstanceView&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineAgentInstanceView" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineAgentInstanceView (vmAgentVersion, extensionHandlers, statuses)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="vmAgentVersion" Type="System.String" />
        <Parameter Name="extensionHandlers" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionHandlerInstanceView&gt;" />
        <Parameter Name="statuses" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus&gt;" />
      </Parameters>
      <Docs>
        <param name="vmAgentVersion">Die vollständige Version des VM-Agent.</param>
        <param name="extensionHandlers">Die virtuelle Maschine Erweiterung Handler Instanzansicht.</param>
        <param name="statuses">Die Statusinformationen für die Ressource.</param>
        <summary>
            Initialisiert eine neue Instanz der VirtualMachineAgentInstanceView-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtensionHandlers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionHandlerInstanceView&gt; ExtensionHandlers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionHandlerInstanceView&gt; ExtensionHandlers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineAgentInstanceView.ExtensionHandlers" />
      <MemberSignature Language="VB.NET" Value="Public Property ExtensionHandlers As IList(Of VirtualMachineExtensionHandlerInstanceView)" />
      <MemberSignature Language="F#" Value="member this.ExtensionHandlers : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionHandlerInstanceView&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineAgentInstanceView.ExtensionHandlers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="extensionHandlers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionHandlerInstanceView&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den VM-Erweiterungshandler Instanzansicht.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Statuses">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus&gt; Statuses { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus&gt; Statuses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineAgentInstanceView.Statuses" />
      <MemberSignature Language="VB.NET" Value="Public Property Statuses As IList(Of InstanceViewStatus)" />
      <MemberSignature Language="F#" Value="member this.Statuses : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineAgentInstanceView.Statuses" />
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
            Ruft ab oder legt die Statusinformationen für die Ressource.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VmAgentVersion">
      <MemberSignature Language="C#" Value="public string VmAgentVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VmAgentVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineAgentInstanceView.VmAgentVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property VmAgentVersion As String" />
      <MemberSignature Language="F#" Value="member this.VmAgentVersion : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineAgentInstanceView.VmAgentVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vmAgentVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Vollversion von VM-Agent.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>