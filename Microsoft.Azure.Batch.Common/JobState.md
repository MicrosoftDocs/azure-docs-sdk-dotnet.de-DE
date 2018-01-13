<Type Name="JobState" FullName="Microsoft.Azure.Batch.Common.JobState">
  <TypeSignature Language="C#" Value="public enum JobState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed JobState extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.JobState" />
  <TypeSignature Language="VB.NET" Value="Public Enum JobState" />
  <TypeSignature Language="F#" Value="type JobState = " />
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
            Den Status des Auftrags
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Active">
      <MemberSignature Language="C#" Value="Active" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.JobState Active = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.JobState.Active" />
      <MemberSignature Language="VB.NET" Value="Active" />
      <MemberSignature Language="F#" Value="Active = 0" Usage="Microsoft.Azure.Batch.Common.JobState.Active" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.JobState</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            Der Auftrag wird für geplante Aufgaben sind verfügbar.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Completed">
      <MemberSignature Language="C#" Value="Completed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.JobState Completed = int32(5)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.JobState.Completed" />
      <MemberSignature Language="VB.NET" Value="Completed" />
      <MemberSignature Language="F#" Value="Completed = 5" Usage="Microsoft.Azure.Batch.Common.JobState.Completed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.JobState</ReturnType>
      </ReturnValue>
      <MemberValue>5</MemberValue>
      <Docs>
        <summary>
            Alle Aufgaben beendet haben, und das System nimmt alle Weitere Aufgaben oder weiteren Änderungen an den Auftrag.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Deleting">
      <MemberSignature Language="C#" Value="Deleting" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.JobState Deleting = int32(6)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.JobState.Deleting" />
      <MemberSignature Language="VB.NET" Value="Deleting" />
      <MemberSignature Language="F#" Value="Deleting = 6" Usage="Microsoft.Azure.Batch.Common.JobState.Deleting" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.JobState</ReturnType>
      </ReturnValue>
      <MemberValue>6</MemberValue>
      <Docs>
        <summary>
            Ein Benutzer hat angefordert, dass der Auftrag gelöscht werden, aber der Löschvorgang ist noch in Bearbeitung (z. B. weil das System dennoch Ausführen von Aufgaben beendet wird).
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Disabled">
      <MemberSignature Language="C#" Value="Disabled" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.JobState Disabled = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.JobState.Disabled" />
      <MemberSignature Language="VB.NET" Value="Disabled" />
      <MemberSignature Language="F#" Value="Disabled = 2" Usage="Microsoft.Azure.Batch.Common.JobState.Disabled" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.JobState</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            Ein Benutzer hat den Auftrag deaktiviert. Keine Aufgaben ausgeführt werden, und werden keine neue Tasks geplant werden.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Disabling">
      <MemberSignature Language="C#" Value="Disabling" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.JobState Disabling = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.JobState.Disabling" />
      <MemberSignature Language="VB.NET" Value="Disabling" />
      <MemberSignature Language="F#" Value="Disabling = 1" Usage="Microsoft.Azure.Batch.Common.JobState.Disabling" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.JobState</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            Ein Benutzer hat angefordert, dass der Auftrag deaktiviert werden, aber der Deaktivierungsvorgang ist noch in Bearbeitung (z. B. beim Warten auf die Aufgaben beendet).
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Enabling">
      <MemberSignature Language="C#" Value="Enabling" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.JobState Enabling = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.JobState.Enabling" />
      <MemberSignature Language="VB.NET" Value="Enabling" />
      <MemberSignature Language="F#" Value="Enabling = 3" Usage="Microsoft.Azure.Batch.Common.JobState.Enabling" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.JobState</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            Ein Benutzer hat angefordert, dass der Auftrag aktiviert werden, aber der Aktivierungsvorgang ist noch nicht abgeschlossen.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Terminating">
      <MemberSignature Language="C#" Value="Terminating" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.JobState Terminating = int32(4)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.JobState.Terminating" />
      <MemberSignature Language="VB.NET" Value="Terminating" />
      <MemberSignature Language="F#" Value="Terminating = 4" Usage="Microsoft.Azure.Batch.Common.JobState.Terminating" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.JobState</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
            Der Auftrag ist zum Abschließen, weil eine Auftrags-Manager-Aufgabe abgeschlossen wurde oder der Benutzer, den Auftrag beendet wurde, aber der Vorgang "Beenden" noch in Bearbeitung wird (z. B. weil der Auftrag Version Aufgaben ausgeführt werden).
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>