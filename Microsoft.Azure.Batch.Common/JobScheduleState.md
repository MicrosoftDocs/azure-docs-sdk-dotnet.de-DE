<Type Name="JobScheduleState" FullName="Microsoft.Azure.Batch.Common.JobScheduleState">
  <TypeSignature Language="C#" Value="public enum JobScheduleState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed JobScheduleState extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.JobScheduleState" />
  <TypeSignature Language="VB.NET" Value="Public Enum JobScheduleState" />
  <TypeSignature Language="F#" Value="type JobScheduleState = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            Der Status der Zeitplan für einen Auftrag.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Active">
      <MemberSignature Language="C#" Value="Active" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.JobScheduleState Active = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.JobScheduleState.Active" />
      <MemberSignature Language="VB.NET" Value="Active" />
      <MemberSignature Language="F#" Value="Active = 0" Usage="Microsoft.Azure.Batch.Common.JobScheduleState.Active" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.JobScheduleState</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            Der Auftragszeitplan aktiv ist und Aufträge gemäß dem Zeitplan erstellt.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Completed">
      <MemberSignature Language="C#" Value="Completed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.JobScheduleState Completed = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.JobScheduleState.Completed" />
      <MemberSignature Language="VB.NET" Value="Completed" />
      <MemberSignature Language="F#" Value="Completed = 1" Usage="Microsoft.Azure.Batch.Common.JobScheduleState.Completed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.JobScheduleState</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            Der Zeitplan wurde durch seine Endzeit erreichen oder vom Benutzer beendet er explizit beendet.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Deleting">
      <MemberSignature Language="C#" Value="Deleting" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.JobScheduleState Deleting = int32(4)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.JobScheduleState.Deleting" />
      <MemberSignature Language="VB.NET" Value="Deleting" />
      <MemberSignature Language="F#" Value="Deleting = 4" Usage="Microsoft.Azure.Batch.Common.JobScheduleState.Deleting" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.JobScheduleState</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
            Der Benutzer fordert, dass der Zeitplan gelöscht werden, aber der Delete-Vorgang wird noch ausgeführt. Der Planer keine neuen Aufträge für diesen Zeitplan nicht initiiert, aber alle vorhandener aktiven Auftrag wird weiterhin ausgeführt. Der Zeitplan wird gelöscht werden, wenn der vorhandene Auftrag abgeschlossen ist.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Disabled">
      <MemberSignature Language="C#" Value="Disabled" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.JobScheduleState Disabled = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.JobScheduleState.Disabled" />
      <MemberSignature Language="VB.NET" Value="Disabled" />
      <MemberSignature Language="F#" Value="Disabled = 2" Usage="Microsoft.Azure.Batch.Common.JobScheduleState.Disabled" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.JobScheduleState</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            Der Benutzer hat den Zeitplan deaktiviert. Der Planer neuen Aufträge werden über diesen Zeitplan nicht initiiert, aber alle vorhandener aktiven Auftrag wird weiterhin ausgeführt.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Terminating">
      <MemberSignature Language="C#" Value="Terminating" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.JobScheduleState Terminating = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.JobScheduleState.Terminating" />
      <MemberSignature Language="VB.NET" Value="Terminating" />
      <MemberSignature Language="F#" Value="Terminating = 3" Usage="Microsoft.Azure.Batch.Common.JobScheduleState.Terminating" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.JobScheduleState</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            Der Zeitplan wurde nicht mehr Arbeit, oder Sie wurde explizit vom Benutzer beendet, aber der beenden-Vorgang wird noch ausgeführt. Der Planer keine neuen Aufträge für diesen Zeitplan nicht initiiert werden, noch wird ein vorhandener Auftrag aktiv.
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>