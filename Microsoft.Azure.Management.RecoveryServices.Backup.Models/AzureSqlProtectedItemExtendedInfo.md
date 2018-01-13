<Type Name="AzureSqlProtectedItemExtendedInfo" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItemExtendedInfo">
  <TypeSignature Language="C#" Value="public class AzureSqlProtectedItemExtendedInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureSqlProtectedItemExtendedInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItemExtendedInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureSqlProtectedItemExtendedInfo" />
  <TypeSignature Language="F#" Value="type AzureSqlProtectedItemExtendedInfo = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Weitere Informationen zu Sql Azure spezifische geschützte Element.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureSqlProtectedItemExtendedInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItemExtendedInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der AzureSqlProtectedItemExtendedInfo-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureSqlProtectedItemExtendedInfo (Nullable&lt;DateTime&gt; oldestRecoveryPoint = null, Nullable&lt;int&gt; recoveryPointCount = null, string policyState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; oldestRecoveryPoint, valuetype System.Nullable`1&lt;int32&gt; recoveryPointCount, string policyState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItemExtendedInfo.#ctor(System.Nullable{System.DateTime},System.Nullable{System.Int32},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional oldestRecoveryPoint As Nullable(Of DateTime) = null, Optional recoveryPointCount As Nullable(Of Integer) = null, Optional policyState As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItemExtendedInfo : Nullable&lt;DateTime&gt; * Nullable&lt;int&gt; * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItemExtendedInfo" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItemExtendedInfo (oldestRecoveryPoint, recoveryPointCount, policyState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="oldestRecoveryPoint" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="recoveryPointCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="policyState" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="oldestRecoveryPoint">Die älteste Sicherungskopie für dieses Element in den Dienst verfügbar.</param>
        <param name="recoveryPointCount">Die Anzahl der verfügbaren Sicherungskopien dieser Sichern des Elements zugeordnet.</param>
        <param name="policyState">Status der Sicherungsrichtlinie dieser Sichern des Elements zugeordnet.</param>
        <summary>
            Initialisiert eine neue Instanz der AzureSqlProtectedItemExtendedInfo-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OldestRecoveryPoint">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; OldestRecoveryPoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; OldestRecoveryPoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItemExtendedInfo.OldestRecoveryPoint" />
      <MemberSignature Language="VB.NET" Value="Public Property OldestRecoveryPoint As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.OldestRecoveryPoint : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItemExtendedInfo.OldestRecoveryPoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="oldestRecoveryPoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die älteste Sicherungskopie erstellen, die für dieses Element im Dienst.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PolicyState">
      <MemberSignature Language="C#" Value="public string PolicyState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PolicyState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItemExtendedInfo.PolicyState" />
      <MemberSignature Language="VB.NET" Value="Public Property PolicyState As String" />
      <MemberSignature Language="F#" Value="member this.PolicyState : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItemExtendedInfo.PolicyState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="policyState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest der Sicherungsrichtlinie verknüpft sind mit diesem Element für die Sicherung.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryPointCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RecoveryPointCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RecoveryPointCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItemExtendedInfo.RecoveryPointCount" />
      <MemberSignature Language="VB.NET" Value="Public Property RecoveryPointCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RecoveryPointCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItemExtendedInfo.RecoveryPointCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recoveryPointCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Anzahl der verfügbaren Sicherungskopien dieser Sichern des Elements zugeordnet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>