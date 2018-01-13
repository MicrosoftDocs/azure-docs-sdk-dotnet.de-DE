<Type Name="ComputeNodeReimageOption" FullName="Microsoft.Azure.Batch.Common.ComputeNodeReimageOption">
  <TypeSignature Language="C#" Value="public enum ComputeNodeReimageOption" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ComputeNodeReimageOption extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.ComputeNodeReimageOption" />
  <TypeSignature Language="VB.NET" Value="Public Enum ComputeNodeReimageOption" />
  <TypeSignature Language="F#" Value="type ComputeNodeReimageOption = " />
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
            Gibt an, wann die Serverknoten reimaging durchführen und was mit den derzeit ausgeführten Tasks geschehen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Requeue">
      <MemberSignature Language="C#" Value="Requeue" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeReimageOption Requeue = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeReimageOption.Requeue" />
      <MemberSignature Language="VB.NET" Value="Requeue" />
      <MemberSignature Language="F#" Value="Requeue = 0" Usage="Microsoft.Azure.Batch.Common.ComputeNodeReimageOption.Requeue" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeReimageOption</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            Beenden Sie derzeit ausgeführte Tasks, und sie requeue. Die Tasks werden erneut ausgeführt, sobald der Auftrag aktiviert ist. Stellen Sie Serverknoten als Tasks abgeschlossen wurden.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="RetainedData">
      <MemberSignature Language="C#" Value="RetainedData" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeReimageOption RetainedData = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeReimageOption.RetainedData" />
      <MemberSignature Language="VB.NET" Value="RetainedData" />
      <MemberSignature Language="F#" Value="RetainedData = 3" Usage="Microsoft.Azure.Batch.Common.ComputeNodeReimageOption.RetainedData" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeReimageOption</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            Ermöglichen Sie die aktuell ausgeführter Aufgaben abgeschlossen ist, und warten Sie, bis alle Aufgabe Beibehaltungsdauer abläuft. Planen Sie beim Warten keine neuen Tasks. Ein reimaging ausführen Sie den Compute-Knoten, wenn die Aufbewahrungsdauer für alle Tasks abgelaufen sind.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="TaskCompletion">
      <MemberSignature Language="C#" Value="TaskCompletion" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeReimageOption TaskCompletion = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeReimageOption.TaskCompletion" />
      <MemberSignature Language="VB.NET" Value="TaskCompletion" />
      <MemberSignature Language="F#" Value="TaskCompletion = 2" Usage="Microsoft.Azure.Batch.Common.ComputeNodeReimageOption.TaskCompletion" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeReimageOption</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            Ermöglichen Sie die derzeit ausgeführten Tasks ab. Planen Sie beim Warten keine neuen Tasks. Ein reimaging ausführen Sie den Computeknoten, wenn alle Aufgaben abgeschlossen wurden.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Terminate">
      <MemberSignature Language="C#" Value="Terminate" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeReimageOption Terminate = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeReimageOption.Terminate" />
      <MemberSignature Language="VB.NET" Value="Terminate" />
      <MemberSignature Language="F#" Value="Terminate = 1" Usage="Microsoft.Azure.Batch.Common.ComputeNodeReimageOption.Terminate" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeReimageOption</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            Ausführen von Aufgaben zu beenden. Die Tasks werden nicht erneut ausgeführt. Stellen Sie Serverknoten als Tasks abgeschlossen wurden.
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>