<Type Name="ComputeNodeDeallocationOption" FullName="Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption">
  <TypeSignature Language="C#" Value="public enum ComputeNodeDeallocationOption" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ComputeNodeDeallocationOption extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption" />
  <TypeSignature Language="VB.NET" Value="Public Enum ComputeNodeDeallocationOption" />
  <TypeSignature Language="F#" Value="type ComputeNodeDeallocationOption = " />
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
            Gibt an, wie behandelt Aufgaben bereits ausgeführt wird und wenn ressourcenaufwändig Knoten möglicherweise aus dem Pool entfernt werden, wenn Verkleinerung des Pools.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Requeue">
      <MemberSignature Language="C#" Value="Requeue" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption Requeue = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />
      <MemberSignature Language="VB.NET" Value="Requeue" />
      <MemberSignature Language="F#" Value="Requeue = 0" Usage="Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            Beenden Sie derzeit ausgeführte Tasks, und sie requeue. Die Tasks werden erneut ausgeführt, sobald der Auftrag aktiviert ist. Entfernen Sie Knoten, sobald Tasks abgeschlossen wurden.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="RetainedData">
      <MemberSignature Language="C#" Value="RetainedData" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption RetainedData = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.RetainedData" />
      <MemberSignature Language="VB.NET" Value="RetainedData" />
      <MemberSignature Language="F#" Value="RetainedData = 3" Usage="Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.RetainedData" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            Ermöglichen Sie die aktuell ausgeführter Aufgaben abgeschlossen ist, und warten Sie, bis alle Aufgabe Beibehaltungsdauer abläuft. Planen Sie beim Warten keine neuen Tasks. Entfernen Sie Knoten, sobald die Aufbewahrungszeiträume aller Tasks abgelaufen sind.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="TaskCompletion">
      <MemberSignature Language="C#" Value="TaskCompletion" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption TaskCompletion = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.TaskCompletion" />
      <MemberSignature Language="VB.NET" Value="TaskCompletion" />
      <MemberSignature Language="F#" Value="TaskCompletion = 2" Usage="Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.TaskCompletion" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            Ermöglichen Sie die derzeit ausgeführten Tasks ab. Planen Sie beim Warten keine neuen Tasks. Entfernen Sie Knoten, sobald alle Aufgaben abgeschlossen sind.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Terminate">
      <MemberSignature Language="C#" Value="Terminate" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption Terminate = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Terminate" />
      <MemberSignature Language="VB.NET" Value="Terminate" />
      <MemberSignature Language="F#" Value="Terminate = 1" Usage="Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Terminate" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            Ausführen von Aufgaben zu beenden. Die Tasks werden nicht erneut ausgeführt. Entfernen Sie Knoten, sobald Tasks abgeschlossen wurden.
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>