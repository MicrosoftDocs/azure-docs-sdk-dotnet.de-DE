<Type Name="VirtualMachineExtensionHandlerInstanceView" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionHandlerInstanceView">
  <TypeSignature Language="C#" Value="public class VirtualMachineExtensionHandlerInstanceView" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualMachineExtensionHandlerInstanceView extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionHandlerInstanceView" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualMachineExtensionHandlerInstanceView" />
  <TypeSignature Language="F#" Value="type VirtualMachineExtensionHandlerInstanceView = class" />
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
            Die Instanzansicht von einem VM-Erweiterungshandler.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineExtensionHandlerInstanceView ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionHandlerInstanceView.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der VirtualMachineExtensionHandlerInstanceView-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualMachineExtensionHandlerInstanceView (string type = null, string typeHandlerVersion = null, Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus status = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string type, string typeHandlerVersion, class Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus status) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionHandlerInstanceView.#ctor(System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional type As String = null, Optional typeHandlerVersion As String = null, Optional status As InstanceViewStatus = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionHandlerInstanceView : string * string * Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionHandlerInstanceView" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionHandlerInstanceView (type, typeHandlerVersion, status)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="typeHandlerVersion" Type="System.String" />
        <Parameter Name="status" Type="Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus" />
      </Parameters>
      <Docs>
        <param name="type">Vollständige Typ des erweiterungshandlers dem Verleger und Typ enthält.</param>
        <param name="typeHandlerVersion">Die Version des erweiterungshandlers.</param>
        <param name="status">Den Erweiterungsstatus Handler.</param>
        <summary>
            Initialisiert eine neue Instanz der VirtualMachineExtensionHandlerInstanceView-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionHandlerInstanceView.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As InstanceViewStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionHandlerInstanceView.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Handler Erweiterungsstatus.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionHandlerInstanceView.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionHandlerInstanceView.Type" />
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
            Ruft ab oder legt ihn fest vollständige anwendungserweiterungs-Handler, der Verleger und Typ enthält.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TypeHandlerVersion">
      <MemberSignature Language="C#" Value="public string TypeHandlerVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TypeHandlerVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionHandlerInstanceView.TypeHandlerVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property TypeHandlerVersion As String" />
      <MemberSignature Language="F#" Value="member this.TypeHandlerVersion : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineExtensionHandlerInstanceView.TypeHandlerVersion" />
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
            Ruft ab oder legt die Version des erweiterungshandlers.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>