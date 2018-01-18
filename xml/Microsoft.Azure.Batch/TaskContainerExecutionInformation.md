<Type Name="TaskContainerExecutionInformation" FullName="Microsoft.Azure.Batch.TaskContainerExecutionInformation">
  <TypeSignature Language="C#" Value="public class TaskContainerExecutionInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskContainerExecutionInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.TaskContainerExecutionInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskContainerExecutionInformation" />
  <TypeSignature Language="F#" Value="type TaskContainerExecutionInformation = class&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="79708-101">Enthält Informationen über den Container, die eine Aufgabe ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="79708-101">Contains information about the container which a task is executing.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ContainerId">
      <MemberSignature Language="C#" Value="public string ContainerId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContainerId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskContainerExecutionInformation.ContainerId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContainerId As String" />
      <MemberSignature Language="F#" Value="member this.ContainerId : string" Usage="Microsoft.Azure.Batch.TaskContainerExecutionInformation.ContainerId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="79708-102">Ruft die ID des Containers ab.</span><span class="sxs-lookup"><span data-stu-id="79708-102">Gets the ID of the container.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public string Error { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Error" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskContainerExecutionInformation.Error" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Error As String" />
      <MemberSignature Language="F#" Value="member this.Error : string" Usage="Microsoft.Azure.Batch.TaskContainerExecutionInformation.Error" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="79708-103">Ruft ausführliche Fehlerinformationen über den Container.</span><span class="sxs-lookup"><span data-stu-id="79708-103">Gets detailed error information about the container.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="79708-104">Dies ist die detaillierte Fehlerzeichenfolge aus dem Docker-Dienst, falls verfügbar.</span><span class="sxs-lookup"><span data-stu-id="79708-104">This is the detailed error string from the Docker service, if available.</span></span> <span data-ttu-id="79708-105">Es entspricht Fehlerfeld von "Docker überprüfen" zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="79708-105">It is equivilant to the error field returned by "docker inspect".</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskContainerExecutionInformation.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string" Usage="Microsoft.Azure.Batch.TaskContainerExecutionInformation.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="79708-106">Ruft den Zustand des Containers ab.</span><span class="sxs-lookup"><span data-stu-id="79708-106">Gets the state of the container.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="79708-107">Dies ist der Zustand des Containers entsprechend den Docker-Dienst.</span><span class="sxs-lookup"><span data-stu-id="79708-107">This is the state of the container according to the Docker service.</span></span> <span data-ttu-id="79708-108">Es entspricht das Statusfeld zurückgegebenes "Docker überprüfen".</span><span class="sxs-lookup"><span data-stu-id="79708-108">It is equivilant to the status field returned by "docker inspect".</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>