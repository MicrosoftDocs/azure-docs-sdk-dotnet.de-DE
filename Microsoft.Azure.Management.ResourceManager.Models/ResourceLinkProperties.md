<Type Name="ResourceLinkProperties" FullName="Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkProperties">
  <TypeSignature Language="C#" Value="public class ResourceLinkProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceLinkProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceLinkProperties" />
  <TypeSignature Language="F#" Value="type ResourceLinkProperties = class" />
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
            Die Verknüpfungseigenschaften für die Ressource.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceLinkProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ResourceLinkProperties-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceLinkProperties (string targetId, string sourceId = null, string notes = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string targetId, string sourceId, string notes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkProperties.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (targetId As String, Optional sourceId As String = null, Optional notes As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkProperties : string * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkProperties" Usage="new Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkProperties (targetId, sourceId, notes)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="targetId" Type="System.String" />
        <Parameter Name="sourceId" Type="System.String" />
        <Parameter Name="notes" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="targetId">Die vollqualifizierte ID der Zielressource unter folgendem Link.</param>
        <param name="sourceId">Die vollqualifizierte ID der quellressource im Link. </param>
        <param name="notes">Hinweise zu den ressourcenlink.</param>
        <summary>
            Initialisiert eine neue Instanz der ResourceLinkProperties-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Notes">
      <MemberSignature Language="C#" Value="public string Notes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Notes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkProperties.Notes" />
      <MemberSignature Language="VB.NET" Value="Public Property Notes As String" />
      <MemberSignature Language="F#" Value="member this.Notes : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkProperties.Notes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="notes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt Sie Hinweise zu den ressourcenlink fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceId">
      <MemberSignature Language="C#" Value="public string SourceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkProperties.SourceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SourceId As String" />
      <MemberSignature Language="F#" Value="member this.SourceId : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkProperties.SourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die vollqualifizierte ID der quellressource im Link ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetId">
      <MemberSignature Language="C#" Value="public string TargetId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkProperties.TargetId" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetId As String" />
      <MemberSignature Language="F#" Value="member this.TargetId : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkProperties.TargetId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die vollständig qualifizierte ID der Zielressource unter folgendem Link.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkProperties.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="resourceLinkProperties.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>