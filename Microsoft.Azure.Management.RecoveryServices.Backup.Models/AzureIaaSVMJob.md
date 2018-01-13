<Type Name="AzureIaaSVMJob" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJob">
  <TypeSignature Language="C#" Value="public class AzureIaaSVMJob : Microsoft.Azure.Management.RecoveryServices.Backup.Models.Job" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureIaaSVMJob extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.Job" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJob" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureIaaSVMJob&#xA;Inherits Job" />
  <TypeSignature Language="F#" Value="type AzureIaaSVMJob = class&#xA;    inherit Job" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Backup.Models.Job</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Azure IaaS-VM Arbeitslast bestimmter Job-Objekt.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureIaaSVMJob ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJob.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der AzureIaaSVMJob-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureIaaSVMJob (string entityFriendlyName = null, string backupManagementType = null, string operation = null, string status = null, Nullable&lt;DateTime&gt; startTime = null, Nullable&lt;DateTime&gt; endTime = null, string activityId = null, Nullable&lt;TimeSpan&gt; duration = null, System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobSupportedAction&gt;&gt; actionsInfo = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMErrorInfo&gt; errorDetails = null, string virtualMachineVersion = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJobExtendedInfo extendedInfo = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string entityFriendlyName, string backupManagementType, string operation, string status, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, string activityId, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; duration, class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobSupportedAction&gt;&gt; actionsInfo, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMErrorInfo&gt; errorDetails, string virtualMachineVersion, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJobExtendedInfo extendedInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJob.#ctor(System.String,System.String,System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.Nullable{System.TimeSpan},System.Collections.Generic.IList{System.Nullable{Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobSupportedAction}},System.Collections.Generic.IList{Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMErrorInfo},System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJobExtendedInfo)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional entityFriendlyName As String = null, Optional backupManagementType As String = null, Optional operation As String = null, Optional status As String = null, Optional startTime As Nullable(Of DateTime) = null, Optional endTime As Nullable(Of DateTime) = null, Optional activityId As String = null, Optional duration As Nullable(Of TimeSpan) = null, Optional actionsInfo As IList(Of Nullable(Of JobSupportedAction)) = null, Optional errorDetails As IList(Of AzureIaaSVMErrorInfo) = null, Optional virtualMachineVersion As String = null, Optional extendedInfo As AzureIaaSVMJobExtendedInfo = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJob : string * string * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * Nullable&lt;TimeSpan&gt; * System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobSupportedAction&gt;&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMErrorInfo&gt; * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJobExtendedInfo -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJob" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJob (entityFriendlyName, backupManagementType, operation, status, startTime, endTime, activityId, duration, actionsInfo, errorDetails, virtualMachineVersion, extendedInfo)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="entityFriendlyName" Type="System.String" />
        <Parameter Name="backupManagementType" Type="System.String" />
        <Parameter Name="operation" Type="System.String" />
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="activityId" Type="System.String" />
        <Parameter Name="duration" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="actionsInfo" Type="System.Collections.Generic.IList&lt;System.Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobSupportedAction&gt;&gt;" />
        <Parameter Name="errorDetails" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMErrorInfo&gt;" />
        <Parameter Name="virtualMachineVersion" Type="System.String" />
        <Parameter Name="extendedInfo" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJobExtendedInfo" />
      </Parameters>
      <Docs>
        <param name="entityFriendlyName">Anzeigename der Entität, auf der der aktuelle Auftrag ausgeführt wird.</param>
        <param name="backupManagementType">Sicherungsverwaltung-Typ, der den aktuellen Auftrag ausführt. Folgende Werte sind möglich: "Ungültig", "AzureIaasVM", "MAB", "DPM", "AzureBackupServer", "Azure SQL"</param>
        <param name="operation">Der Name des Vorgangs.</param>
        <param name="status">Status des Auftrags.</param>
        <param name="startTime">Die Startzeit.</param>
        <param name="endTime">Die Endzeit.</param>
        <param name="activityId">Aktivitäts-ID des Auftrags.</param>
        <param name="duration">Verstrichene Zeit, während der Ausführung des Auftrags.</param>
        <param name="actionsInfo">Ruft ab oder legt ihn fest/statusaktionen anwendbar zu diesem Auftrag z. B. "Abbrechen" / "Wiederholen".</param>
        <param name="errorDetails">Details zum Systemfehler bei der Ausführung des Auftrags.</param>
        <param name="virtualMachineVersion">Gibt an, ob das Element für die Sicherung einer klassischen oder einer Azure-Ressourcen-Manager-VM ist.</param>
        <param name="extendedInfo">Zusätzliche Informationen für diesen Auftrag.</param>
        <summary>
            Initialisiert eine neue Instanz der AzureIaaSVMJob-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActionsInfo">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobSupportedAction&gt;&gt; ActionsInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobSupportedAction&gt;&gt; ActionsInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJob.ActionsInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property ActionsInfo As IList(Of Nullable(Of JobSupportedAction))" />
      <MemberSignature Language="F#" Value="member this.ActionsInfo : System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobSupportedAction&gt;&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJob.ActionsInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="actionsInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Nullable&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobSupportedAction&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest/statusaktionen anwendbar zu diesem Auftrag z. B. "Abbrechen" / "Wiederholen".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Duration">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; Duration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; Duration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJob.Duration" />
      <MemberSignature Language="VB.NET" Value="Public Property Duration As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.Duration : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJob.Duration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="duration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest verstrichene Zeit, während der Ausführung des Auftrags.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorDetails">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMErrorInfo&gt; ErrorDetails { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMErrorInfo&gt; ErrorDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJob.ErrorDetails" />
      <MemberSignature Language="VB.NET" Value="Public Property ErrorDetails As IList(Of AzureIaaSVMErrorInfo)" />
      <MemberSignature Language="F#" Value="member this.ErrorDetails : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMErrorInfo&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJob.ErrorDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="errorDetails")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMErrorInfo&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Details zum Systemfehler bei der Ausführung des Auftrags.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtendedInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJobExtendedInfo ExtendedInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJobExtendedInfo ExtendedInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJob.ExtendedInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property ExtendedInfo As AzureIaaSVMJobExtendedInfo" />
      <MemberSignature Language="F#" Value="member this.ExtendedInfo : Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJobExtendedInfo with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJob.ExtendedInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="extendedInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJobExtendedInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt zusätzliche Informationen für diesen Auftrag.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineVersion">
      <MemberSignature Language="C#" Value="public string VirtualMachineVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VirtualMachineVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJob.VirtualMachineVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualMachineVersion As String" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineVersion : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMJob.VirtualMachineVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="virtualMachineVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest gibt an, ob das Element für die Sicherung einer klassischen oder einer Azure-Ressourcen-Manager-VM ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>