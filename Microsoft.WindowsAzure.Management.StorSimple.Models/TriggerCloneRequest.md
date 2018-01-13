<Type Name="TriggerCloneRequest" FullName="Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest">
  <TypeSignature Language="C#" Value="public class TriggerCloneRequest" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TriggerCloneRequest extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class TriggerCloneRequest" />
  <TypeSignature Language="F#" Value="type TriggerCloneRequest = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Diese Klasse die darstellt die Details für die klonanforderung
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TriggerCloneRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der TriggerCloneRequest-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupSetId">
      <MemberSignature Language="C#" Value="public string BackupSetId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackupSetId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest.BackupSetId" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupSetId As String" />
      <MemberSignature Language="F#" Value="member this.BackupSetId : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest.BackupSetId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Erforderlich. Die Id des Sicherungssatzes, das die aktuelle Momentaufnahme gehört
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReturnWorkflowId">
      <MemberSignature Language="C#" Value="public bool ReturnWorkflowId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ReturnWorkflowId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest.ReturnWorkflowId" />
      <MemberSignature Language="VB.NET" Value="Public Property ReturnWorkflowId As Boolean" />
      <MemberSignature Language="F#" Value="member this.ReturnWorkflowId : bool with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest.ReturnWorkflowId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Optional. Legt fest, ob die Methode die WorkflowId zurückgibt
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceSnapshot">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.Models.Snapshot SourceSnapshot { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.Models.Snapshot SourceSnapshot" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest.SourceSnapshot" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceSnapshot As Snapshot" />
      <MemberSignature Language="F#" Value="member this.SourceSnapshot : Microsoft.WindowsAzure.Management.StorSimple.Models.Snapshot with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest.SourceSnapshot" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.Snapshot</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Erforderlich. Momentaufnahme von einer Sicherung zu klonenden also
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetACRIdList">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; TargetACRIdList { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; TargetACRIdList" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest.TargetACRIdList" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetACRIdList As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.TargetACRIdList : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest.TargetACRIdList" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Optional. Liste der vorhandenen zugriffssteuerungsdatensätze das geklonte Volume hinzu
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetACRList">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.AccessControlRecord&gt; TargetACRList { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.AccessControlRecord&gt; TargetACRList" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest.TargetACRList" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetACRList As IList(Of AccessControlRecord)" />
      <MemberSignature Language="F#" Value="member this.TargetACRList : System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.AccessControlRecord&gt; with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest.TargetACRList" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.AccessControlRecord&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Optional. Liste der neuen zugriffssteuerungsdatensätze das geklonte Volume hinzu
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetDeviceId">
      <MemberSignature Language="C#" Value="public string TargetDeviceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetDeviceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest.TargetDeviceId" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetDeviceId As String" />
      <MemberSignature Language="F#" Value="member this.TargetDeviceId : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest.TargetDeviceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Erforderlich. Ziel-Geräte-Id, in dem das Volume auf geklont werden müssen
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetVolName">
      <MemberSignature Language="C#" Value="public string TargetVolName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetVolName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest.TargetVolName" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetVolName As String" />
      <MemberSignature Language="F#" Value="member this.TargetVolName : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest.TargetVolName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Erforderlich. Name des geklonten Volumes
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>