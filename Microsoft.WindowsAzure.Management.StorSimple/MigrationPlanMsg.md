<Type Name="MigrationPlanMsg" FullName="Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanMsg">
  <TypeSignature Language="C#" Value="public class MigrationPlanMsg" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MigrationPlanMsg extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanMsg" />
  <TypeSignature Language="VB.NET" Value="Public Class MigrationPlanMsg" />
  <TypeSignature Language="F#" Value="type MigrationPlanMsg = class" />
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
            Allgemeine Migrationsplan für aller Datencontainer importiert nach bestimmten Konfig.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MigrationPlanMsg (Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlan migrationPlan);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlan migrationPlan) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanMsg.#ctor(Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlan)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanMsg : Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlan -&gt; Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanMsg" Usage="new Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanMsg migrationPlan" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="migrationPlan" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlan" />
      </Parameters>
      <Docs>
        <param name="migrationPlan"></param>
        <summary>
            Allgemeine Migrationsplan für eine angegebene Konfiguration erstellen
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviceName">
      <MemberSignature Language="C#" Value="public string DeviceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeviceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanMsg.DeviceName" />
      <MemberSignature Language="VB.NET" Value="Public Property DeviceName As String" />
      <MemberSignature Language="F#" Value="member this.DeviceName : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanMsg.DeviceName" />
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
            Ruft ab oder legt ihn fest zielgerätname.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LegacyConfigId">
      <MemberSignature Language="C#" Value="public string LegacyConfigId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LegacyConfigId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanMsg.LegacyConfigId" />
      <MemberSignature Language="VB.NET" Value="Public Property LegacyConfigId As String" />
      <MemberSignature Language="F#" Value="member this.LegacyConfigId : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanMsg.LegacyConfigId" />
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
            Ruft ab oder legt den eindeutigen Bezeichner der Konfigurationsdatei, deren Migrationsplan abgerufen wird
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MigrationTimeEstimationCompleted">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsgList MigrationTimeEstimationCompleted { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsgList MigrationTimeEstimationCompleted" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanMsg.MigrationTimeEstimationCompleted" />
      <MemberSignature Language="VB.NET" Value="Public Property MigrationTimeEstimationCompleted As MigrationPlanInfoMsgList" />
      <MemberSignature Language="F#" Value="member this.MigrationTimeEstimationCompleted : Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsgList with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanMsg.MigrationTimeEstimationCompleted" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsgList</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Plänen im Status "abgeschlossen"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MigrationTimeEstimationFailed">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsgList MigrationTimeEstimationFailed { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsgList MigrationTimeEstimationFailed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanMsg.MigrationTimeEstimationFailed" />
      <MemberSignature Language="VB.NET" Value="Public Property MigrationTimeEstimationFailed As MigrationPlanInfoMsgList" />
      <MemberSignature Language="F#" Value="member this.MigrationTimeEstimationFailed : Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsgList with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanMsg.MigrationTimeEstimationFailed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsgList</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Plänen im Status "Fehler"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MigrationTimeEstimationInProgress">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsgList MigrationTimeEstimationInProgress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsgList MigrationTimeEstimationInProgress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanMsg.MigrationTimeEstimationInProgress" />
      <MemberSignature Language="VB.NET" Value="Public Property MigrationTimeEstimationInProgress As MigrationPlanInfoMsgList" />
      <MemberSignature Language="F#" Value="member this.MigrationTimeEstimationInProgress : Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsgList with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanMsg.MigrationTimeEstimationInProgress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsgList</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Plänen im Zustand "Bearbeitung"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MigrationTimeEstimationNotStarted">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsgList MigrationTimeEstimationNotStarted { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsgList MigrationTimeEstimationNotStarted" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanMsg.MigrationTimeEstimationNotStarted" />
      <MemberSignature Language="VB.NET" Value="Public Property MigrationTimeEstimationNotStarted As MigrationPlanInfoMsgList" />
      <MemberSignature Language="F#" Value="member this.MigrationTimeEstimationNotStarted : Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsgList with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanMsg.MigrationTimeEstimationNotStarted" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.MigrationPlanInfoMsgList</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Plänen im nicht gestarteten Zustand sind.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>