<Type Name="ResourcesMoveInfo" FullName="Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo">
  <TypeSignature Language="C#" Value="public class ResourcesMoveInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourcesMoveInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourcesMoveInfo" />
  <TypeSignature Language="F#" Value="type ResourcesMoveInfo = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Parameter der Ressourcen verschieben.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourcesMoveInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ResourcesMoveInfo-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourcesMoveInfo (System.Collections.Generic.IList&lt;string&gt; resources = null, string targetResourceGroup = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;string&gt; resources, string targetResourceGroup) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo.#ctor(System.Collections.Generic.IList{System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional resources As IList(Of String) = null, Optional targetResourceGroup As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo : System.Collections.Generic.IList&lt;string&gt; * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo" Usage="new Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo (resources, targetResourceGroup)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="resources" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="targetResourceGroup" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resources">Die Ressourcen-IDs.</param>
        <param name="targetResourceGroup">Die Zielressourcengruppe.</param>
        <summary>
            Initialisiert eine neue Instanz der ResourcesMoveInfo-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resources">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Resources { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Resources" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo.Resources" />
      <MemberSignature Language="VB.NET" Value="Public Property Resources As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Resources : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo.Resources" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resources")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Ressourcen-IDs.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetResourceGroup">
      <MemberSignature Language="C#" Value="public string TargetResourceGroup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetResourceGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo.TargetResourceGroup" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetResourceGroup As String" />
      <MemberSignature Language="F#" Value="member this.TargetResourceGroup : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo.TargetResourceGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetResourceGroup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Zielressourcengruppe.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>