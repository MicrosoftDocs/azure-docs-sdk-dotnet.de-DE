<Type Name="Constants" FullName="Microsoft.Azure.Batch.Constants">
  <TypeSignature Language="C#" Value="public static class Constants" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit Constants extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Constants" />
  <TypeSignature Language="VB.NET" Value="Public Class Constants" />
  <TypeSignature Language="F#" Value="type Constants = class" />
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
            <span data-ttu-id="afed0-101">Enthält Konstanten für die Interaktion mit der Azure Batch-Dienst.</span><span class="sxs-lookup"><span data-stu-id="afed0-101">Contains constants for interacting with the Azure Batch service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefaultConveniencePrefix">
      <MemberSignature Language="C#" Value="public const string DefaultConveniencePrefix;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string DefaultConveniencePrefix" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Constants.DefaultConveniencePrefix" />
      <MemberSignature Language="VB.NET" Value="Public Const DefaultConveniencePrefix As String " />
      <MemberSignature Language="F#" Value="val mutable DefaultConveniencePrefix : string" Usage="Microsoft.Azure.Batch.Constants.DefaultConveniencePrefix" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="afed0-102">Das Präfix beim Erstellen automatisch Container oder Blobs als Teil der Bereitstellung der Datei mit dem Namen verwendet.</span><span class="sxs-lookup"><span data-stu-id="afed0-102">The prefix used when creating automatically named containers or blobs as part of file staging.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultSingleRestRequestClientTimeout">
      <MemberSignature Language="C#" Value="public static readonly TimeSpan DefaultSingleRestRequestClientTimeout;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly valuetype System.TimeSpan DefaultSingleRestRequestClientTimeout" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Constants.DefaultSingleRestRequestClientTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly DefaultSingleRestRequestClientTimeout As TimeSpan " />
      <MemberSignature Language="F#" Value=" staticval mutable DefaultSingleRestRequestClientTimeout : TimeSpan" Usage="Microsoft.Azure.Batch.Constants.DefaultSingleRestRequestClientTimeout" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="afed0-103">Die Standarddauer, die auf eine Antwort von der Batch-Dienst gewartet werden soll, vor dem Abbrechen automatisch der Anforderungs.</span><span class="sxs-lookup"><span data-stu-id="afed0-103">The default amount of time to wait for a response from the Batch service before automatically cancelling the request.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTasksInSingleAddTaskCollectionRequest">
      <MemberSignature Language="C#" Value="public const int MaxTasksInSingleAddTaskCollectionRequest = 100;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal int32 MaxTasksInSingleAddTaskCollectionRequest = (100)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Constants.MaxTasksInSingleAddTaskCollectionRequest" />
      <MemberSignature Language="VB.NET" Value="Public Const MaxTasksInSingleAddTaskCollectionRequest As Integer  = 100" />
      <MemberSignature Language="F#" Value="val mutable MaxTasksInSingleAddTaskCollectionRequest : int" Usage="Microsoft.Azure.Batch.Constants.MaxTasksInSingleAddTaskCollectionRequest" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <MemberValue>100</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="afed0-104">Die maximale Anzahl von Aufgaben, die der Client in einer einzelnen AddTaskCollection-Anforderung enthalten wird, wenn Sie mehrere Aufgaben an einen Auftrag hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="afed0-104">The maximum number of tasks that the client will include in a single AddTaskCollection request, when adding multiple tasks to a job.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StandardErrorFileName">
      <MemberSignature Language="C#" Value="public const string StandardErrorFileName;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string StandardErrorFileName" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Constants.StandardErrorFileName" />
      <MemberSignature Language="VB.NET" Value="Public Const StandardErrorFileName As String " />
      <MemberSignature Language="F#" Value="val mutable StandardErrorFileName : string" Usage="Microsoft.Azure.Batch.Constants.StandardErrorFileName" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="afed0-105">Der Name der generierten Datei von einem Task oder eine Startaufgabe auf einem Serverknoten Standardfehler.</span><span class="sxs-lookup"><span data-stu-id="afed0-105">The name of the standard error file generated by a task or start task on a compute node.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StandardOutFileName">
      <MemberSignature Language="C#" Value="public const string StandardOutFileName;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string StandardOutFileName" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Constants.StandardOutFileName" />
      <MemberSignature Language="VB.NET" Value="Public Const StandardOutFileName As String " />
      <MemberSignature Language="F#" Value="val mutable StandardOutFileName : string" Usage="Microsoft.Azure.Batch.Constants.StandardOutFileName" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="afed0-106">Der Name der generierten Datei von einem Task oder eine Startaufgabe auf einem Serverknoten Standardausgabe.</span><span class="sxs-lookup"><span data-stu-id="afed0-106">The name of the standard output file generated by a task or start task on a compute node.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>