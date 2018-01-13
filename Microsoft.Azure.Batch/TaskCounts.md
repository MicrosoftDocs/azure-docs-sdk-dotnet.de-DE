<Type Name="TaskCounts" FullName="Microsoft.Azure.Batch.TaskCounts">
  <TypeSignature Language="C#" Value="public class TaskCounts" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskCounts extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.TaskCounts" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskCounts" />
  <TypeSignature Language="F#" Value="type TaskCounts = class&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Der Task zählt für einen Auftrag.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Active">
      <MemberSignature Language="C#" Value="public int Active { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Active" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskCounts.Active" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Active As Integer" />
      <MemberSignature Language="F#" Value="member this.Active : int" Usage="Microsoft.Azure.Batch.TaskCounts.Active" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Anzahl der Aufgaben im aktiven Zustand.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Completed">
      <MemberSignature Language="C#" Value="public int Completed { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Completed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskCounts.Completed" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Completed As Integer" />
      <MemberSignature Language="F#" Value="member this.Completed : int" Usage="Microsoft.Azure.Batch.TaskCounts.Completed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Anzahl der Aufgaben in den abgeschlossenen Zustand versetzt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Failed">
      <MemberSignature Language="C#" Value="public int Failed { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Failed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskCounts.Failed" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Failed As Integer" />
      <MemberSignature Language="F#" Value="member this.Failed : int" Usage="Microsoft.Azure.Batch.TaskCounts.Failed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Anzahl der fehlgeschlagenen Aufgaben. Ein Task fehlschlägt, wenn das Ergebnis (in der Eigenschaft ExecutionInfo gefunden) "Failure" ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Running">
      <MemberSignature Language="C#" Value="public int Running { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Running" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskCounts.Running" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Running As Integer" />
      <MemberSignature Language="F#" Value="member this.Running : int" Usage="Microsoft.Azure.Batch.TaskCounts.Running" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Anzahl der Aufgaben in den Zustand ausgeführt werden oder vorbereiten.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Succeeded">
      <MemberSignature Language="C#" Value="public int Succeeded { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Succeeded" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskCounts.Succeeded" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Succeeded As Integer" />
      <MemberSignature Language="F#" Value="member this.Succeeded : int" Usage="Microsoft.Azure.Batch.TaskCounts.Succeeded" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Anzahl der Tasks erfolgreich ab. Eine Aufgabe ist erfolgreich, wenn das Ergebnis (in der Eigenschaft ExecutionInfo gefunden) "Success".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidationStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Common.TaskCountValidationStatus ValidationStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Common.TaskCountValidationStatus ValidationStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskCounts.ValidationStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ValidationStatus As TaskCountValidationStatus" />
      <MemberSignature Language="F#" Value="member this.ValidationStatus : Microsoft.Azure.Batch.Common.TaskCountValidationStatus" Usage="Microsoft.Azure.Batch.TaskCounts.ValidationStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.TaskCountValidationStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, ob die Aufgabe einfach überprüft wurden. Wenn die <see cref="P:Microsoft.Azure.Batch.TaskCounts.ValidationStatus" /> nicht überprüfte, ist, und klicken Sie dann der Batch-Dienst nicht zum Überprüfen des Status für die Aufgabenzustände zählt wurde, wie Sie in der Liste Aufgaben-API können.
            </summary>
        <value>To be added.</value>
        <remarks>
            Die <see cref="P:Microsoft.Azure.Batch.TaskCounts.ValidationStatus" /> möglicherweise nicht überprüfte sein, wenn der Auftrag über 200.000 Aufgaben enthält.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>