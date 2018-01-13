<Type Name="BackupLongTermRetentionPolicy" FullName="Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy">
  <TypeSignature Language="C#" Value="public class BackupLongTermRetentionPolicy : Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackupLongTermRetentionPolicy extends Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class BackupLongTermRetentionPolicy&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type BackupLongTermRetentionPolicy = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Sql.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Eine Aufbewahrungsrichtlinie für die langfristige Sicherung
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupLongTermRetentionPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der BackupLongTermRetentionPolicy-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupLongTermRetentionPolicy (Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicyState state, string recoveryServicesBackupPolicyResourceId, string id = null, string name = null, string type = null, string location = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicyState state, string recoveryServicesBackupPolicyResourceId, string id, string name, string type, string location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy.#ctor(Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicyState,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (state As BackupLongTermRetentionPolicyState, recoveryServicesBackupPolicyResourceId As String, Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional location As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy : Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicyState * string * string * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy" Usage="new Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy (state, recoveryServicesBackupPolicyResourceId, id, name, type, location)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="state" Type="Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicyState" />
        <Parameter Name="recoveryServicesBackupPolicyResourceId" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="state">Der Status der Aufbewahrungsrichtlinie für die langfristige Sicherung. Folgende Werte sind möglich: "Deaktiviert", "Aktiviert"</param>
        <param name="recoveryServicesBackupPolicyResourceId">Sichern Sie den Azure Recovery Services Protection Policy-Ressourcen-id</param>
        <param name="id">Ressourcen-ID</param>
        <param name="name">Name der Ressource.</param>
        <param name="type">Der Ressourcentyp.</param>
        <param name="location">Der geografische Standort, in dem die Ressource aktiv ist</param>
        <summary>
            Initialisiert eine neue Instanz der BackupLongTermRetentionPolicy-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy.Location" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string" Usage="Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den geografischen Standort aktiv ist, in dem die Ressource
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryServicesBackupPolicyResourceId">
      <MemberSignature Language="C#" Value="public string RecoveryServicesBackupPolicyResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RecoveryServicesBackupPolicyResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy.RecoveryServicesBackupPolicyResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property RecoveryServicesBackupPolicyResourceId As String" />
      <MemberSignature Language="F#" Value="member this.RecoveryServicesBackupPolicyResourceId : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy.RecoveryServicesBackupPolicyResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.recoveryServicesBackupPolicyResourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Richtlinie Ressourcen-Id der Azure Recovery Services backup-Schutz
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicyState State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicyState State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy.State" />
      <MemberSignature Language="VB.NET" Value="Public Property State As BackupLongTermRetentionPolicyState" />
      <MemberSignature Language="F#" Value="member this.State : Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicyState with get, set" Usage="Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicyState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Status der Aufbewahrungsrichtlinie für die langfristige Sicherung fest.
            Folgende Werte sind möglich: "Deaktiviert", "Aktiviert"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="backupLongTermRetentionPolicy.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
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