<Type Name="FlowLogInformationInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner">
  <TypeSignature Language="C#" Value="public class FlowLogInformationInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FlowLogInformationInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner" />
  <TypeSignature Language="VB.NET" Value="Public Class FlowLogInformationInner" />
  <TypeSignature Language="F#" Value="type FlowLogInformationInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Informationen über die Konfiguration des Protokolls für Datenfluss.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FlowLogInformationInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der FlowLogInformationInner-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FlowLogInformationInner (string targetResourceId, string storageId, bool enabled, Microsoft.Azure.Management.Network.Fluent.Models.RetentionPolicyParameters retentionPolicy = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string targetResourceId, string storageId, bool enabled, class Microsoft.Azure.Management.Network.Fluent.Models.RetentionPolicyParameters retentionPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner.#ctor(System.String,System.String,System.Boolean,Microsoft.Azure.Management.Network.Fluent.Models.RetentionPolicyParameters)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (targetResourceId As String, storageId As String, enabled As Boolean, Optional retentionPolicy As RetentionPolicyParameters = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner : string * string * bool * Microsoft.Azure.Management.Network.Fluent.Models.RetentionPolicyParameters -&gt; Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner (targetResourceId, storageId, enabled, retentionPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="targetResourceId" Type="System.String" />
        <Parameter Name="storageId" Type="System.String" />
        <Parameter Name="enabled" Type="System.Boolean" />
        <Parameter Name="retentionPolicy" Type="Microsoft.Azure.Management.Network.Fluent.Models.RetentionPolicyParameters" />
      </Parameters>
      <Docs>
        <param name="targetResourceId">Die ID der Ressource für die Datenfluss-Protokollierung zu konfigurieren.</param>
        <param name="storageId">Die ID des Speicherkontos, das die zum Speichern der Datenfluss verwendet wird.</param>
        <param name="enabled">Flag zum Aktivieren/Deaktivieren flow Protokollierung.</param>
        <param name="retentionPolicy">To be added.</param>
        <summary>
            Initialisiert eine neue Instanz der FlowLogInformationInner-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public bool Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.Enabled : bool with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest-Flag aktiviert bzw. deaktiviert die Protokollierung der Datenfluss.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Models.RetentionPolicyParameters RetentionPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.Models.RetentionPolicyParameters RetentionPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner.RetentionPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionPolicy As RetentionPolicyParameters" />
      <MemberSignature Language="F#" Value="member this.RetentionPolicy : Microsoft.Azure.Management.Network.Fluent.Models.RetentionPolicyParameters with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner.RetentionPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.retentionPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Models.RetentionPolicyParameters</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageId">
      <MemberSignature Language="C#" Value="public string StorageId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner.StorageId" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageId As String" />
      <MemberSignature Language="F#" Value="member this.StorageId : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner.StorageId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert die ID des Speicherkontos, das die zum Speichern der Datenfluss verwendet wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetResourceId">
      <MemberSignature Language="C#" Value="public string TargetResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner.TargetResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetResourceId As String" />
      <MemberSignature Language="F#" Value="member this.TargetResourceId : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner.TargetResourceId" />
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
            Ruft ab oder legt die ID der Ressource für die Datenfluss-Protokollierung zu konfigurieren.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.FlowLogInformationInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="flowLogInformationInner.Validate " />
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