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
            Enthält Informationen über den Container, die eine Aufgabe ausgeführt wird.
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
            Ruft die ID des Containers ab.
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
            Ruft ausführliche Fehlerinformationen über den Container.
            </summary>
        <value>To be added.</value>
        <remarks>
            Dies ist die detaillierte Fehlerzeichenfolge aus dem Docker-Dienst, falls verfügbar. Es entspricht Fehlerfeld von "Docker überprüfen" zurückgegeben.
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
            Ruft den Zustand des Containers ab.
            </summary>
        <value>To be added.</value>
        <remarks>
            Dies ist der Zustand des Containers entsprechend den Docker-Dienst. Es entspricht das Statusfeld zurückgegebenes "Docker überprüfen".
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>