<Type Name="TaskContainerExecutionInformation" FullName="Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation">
  <TypeSignature Language="C#" Value="public class TaskContainerExecutionInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskContainerExecutionInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskContainerExecutionInformation" />
  <TypeSignature Language="F#" Value="type TaskContainerExecutionInformation = class" />
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
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskContainerExecutionInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der TaskContainerExecutionInformation-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskContainerExecutionInformation (string containerId = null, string state = null, string error = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string containerId, string state, string error) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional containerId As String = null, Optional state As String = null, Optional error As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation : string * string * string -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation" Usage="new Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation (containerId, state, error)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="containerId" Type="System.String" />
        <Parameter Name="state" Type="System.String" />
        <Parameter Name="error" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="containerId">Die ID des Containers.</param>
        <param name="state">Der Zustand des Containers.</param>
        <param name="error">Ausführliche Fehlerinformationen über den Container.</param>
        <summary>
            Initialisiert eine neue Instanz der TaskContainerExecutionInformation-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerId">
      <MemberSignature Language="C#" Value="public string ContainerId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContainerId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation.ContainerId" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerId As String" />
      <MemberSignature Language="F#" Value="member this.ContainerId : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation.ContainerId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="containerId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die ID des Containers fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public string Error { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Error" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation.Error" />
      <MemberSignature Language="VB.NET" Value="Public Property Error As String" />
      <MemberSignature Language="F#" Value="member this.Error : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation.Error" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="error")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt Sie ausführliche Fehlerinformationen über den Container fest.
            </summary>
        <value>To be added.</value>
        <remarks>
            Dies ist die detaillierte Fehlerzeichenfolge aus dem Docker-Dienst, falls verfügbar. Dies ist äquivalent zum Fehlerfeld von "Docker überprüfen" zurückgegeben.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation.State" />
      <MemberSignature Language="VB.NET" Value="Public Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Zustand des Containers fest.
            </summary>
        <value>To be added.</value>
        <remarks>
            Dies ist der Zustand des Containers entsprechend den Docker-Dienst.
            Dies ist äquivalent zum Statusfeld von "Docker überprüfen" zurückgegeben.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>