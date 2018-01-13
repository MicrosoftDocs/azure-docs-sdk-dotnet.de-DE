<Type Name="JobPreparationTask" FullName="Microsoft.Azure.Batch.JobPreparationTask">
  <TypeSignature Language="C#" Value="public class JobPreparationTask" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobPreparationTask extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.JobPreparationTask" />
  <TypeSignature Language="VB.NET" Value="Public Class JobPreparationTask" />
  <TypeSignature Language="F#" Value="type JobPreparationTask = class&#xA;    interface ITransportObjectProvider&lt;JobPreparationTask&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            Ein Auftrag zur Vorbereitung Task ausführen, bevor alle Aufgaben des Auftrags auf einem gegebenen Knoten zu berechnen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobPreparationTask ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobPreparationTask.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobPreparationTask (string commandLine);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string commandLine) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobPreparationTask.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (commandLine As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.JobPreparationTask : string -&gt; Microsoft.Azure.Batch.JobPreparationTask" Usage="new Microsoft.Azure.Batch.JobPreparationTask commandLine" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="commandLine" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="commandLine">Die Befehlszeile der Aufgabe.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.JobPreparationTask" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommandLine">
      <MemberSignature Language="C#" Value="public string CommandLine { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CommandLine" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobPreparationTask.CommandLine" />
      <MemberSignature Language="VB.NET" Value="Public Property CommandLine As String" />
      <MemberSignature Language="F#" Value="member this.CommandLine : string with get, set" Usage="Microsoft.Azure.Batch.JobPreparationTask.CommandLine" />
      <MemberType>Property</MemberType>
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
            Ruft ab oder legt die Befehlszeile der Aufgabe.
            </summary>
        <value>To be added.</value>
        <remarks>
            Die Befehlszeile wird nicht unter einer Shell ausgeführt, und daher kann nicht nutzen Shell-Funktionen, z. B. umgebungsvariablenerweiterung. Wenn Sie solche Funktionen nutzen möchten, Sie sollten rufen Sie die Befehlsshell in der Befehlszeile z. B. mit "Cmd/c MyCommand" in Windows oder "/ Bin/sh - C MyCommand" unter Linux.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Constraints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.TaskConstraints Constraints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.TaskConstraints Constraints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobPreparationTask.Constraints" />
      <MemberSignature Language="VB.NET" Value="Public Property Constraints As TaskConstraints" />
      <MemberSignature Language="F#" Value="member this.Constraints : Microsoft.Azure.Batch.TaskConstraints with get, set" Usage="Microsoft.Azure.Batch.JobPreparationTask.Constraints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.TaskConstraints</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert vom Benutzer für diesen Auftrag Vorbereitung Task angegebenen ausführungseinschränkungen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.TaskContainerSettings ContainerSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.TaskContainerSettings ContainerSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobPreparationTask.ContainerSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerSettings As TaskContainerSettings" />
      <MemberSignature Language="F#" Value="member this.ContainerSettings : Microsoft.Azure.Batch.TaskContainerSettings with get, set" Usage="Microsoft.Azure.Batch.JobPreparationTask.ContainerSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.TaskContainerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Einstellungen für den Container unter dem der Task ausgeführt wird.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn dies angegeben wird, alle Verzeichnisse rekursiv unterhalb der AZ_BATCH_NODE_ROOT_DIR (der Stamm der Azure Batch-Verzeichnisse auf dem Knoten) in den Container zugeordnet sind, alle Umgebungsvariablen für die Aufgabe in den Container zugeordnet sind und die Befehlszeile der Aufgabe ist in den Container ausgeführt.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvironmentSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.EnvironmentSetting&gt; EnvironmentSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.EnvironmentSetting&gt; EnvironmentSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobPreparationTask.EnvironmentSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property EnvironmentSettings As IList(Of EnvironmentSetting)" />
      <MemberSignature Language="F#" Value="member this.EnvironmentSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.EnvironmentSetting&gt; with get, set" Usage="Microsoft.Azure.Batch.JobPreparationTask.EnvironmentSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.EnvironmentSetting&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Auflistung der EnvironmentSetting-Instanzen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobPreparationTask.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Batch.JobPreparationTask.Id" />
      <MemberType>Property</MemberType>
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
            Ruft ab oder legt die Id des Vorgangs fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RerunOnComputeNodeRebootAfterSuccess">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RerunOnComputeNodeRebootAfterSuccess { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RerunOnComputeNodeRebootAfterSuccess" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobPreparationTask.RerunOnComputeNodeRebootAfterSuccess" />
      <MemberSignature Language="VB.NET" Value="Public Property RerunOnComputeNodeRebootAfterSuccess As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RerunOnComputeNodeRebootAfterSuccess : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.JobPreparationTask.RerunOnComputeNodeRebootAfterSuccess" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, ob der Batch-Dienst den Auftrag zur Vorbereitung Task solange erneut auszuführen sollte nach dem Neustart von eines Serverknotens.
            </summary>
        <value>To be added.</value>
        <remarks>
            Der Auftrag zur Vorbereitung Task immer erneut ausgeführt, wenn ein reimaging ein Compute-Knoten ausgeführt wird oder wenn die Auftrag zur Vorbereitung Aufgabe nicht abgeschlossen wurde (z. B. weil der Neustart ist aufgetreten, während die Aufgabe ausgeführt wurde). Aus diesem Grund sollten Sie immer einen Auftrag zur Vorbereitung Task Idempotent sein und ordnungsgemäß verhält, wenn mehrere Male ausführen schreiben. Wenn diese Eigenschaft nicht angegeben ist, wird der Standardwert lautet "true" vom Batch-Dienst zugewiesen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ResourceFile&gt; ResourceFiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.ResourceFile&gt; ResourceFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobPreparationTask.ResourceFiles" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceFiles As IList(Of ResourceFile)" />
      <MemberSignature Language="F#" Value="member this.ResourceFiles : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ResourceFile&gt; with get, set" Usage="Microsoft.Azure.Batch.JobPreparationTask.ResourceFiles" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ResourceFile&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Liste der Dateien, die der Batch-Dienst auf den Serverknoten herunterlädt, vor dem Ausführen der Befehlszeile.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserIdentity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.UserIdentity UserIdentity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.UserIdentity UserIdentity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobPreparationTask.UserIdentity" />
      <MemberSignature Language="VB.NET" Value="Public Property UserIdentity As UserIdentity" />
      <MemberSignature Language="F#" Value="member this.UserIdentity : Microsoft.Azure.Batch.UserIdentity with get, set" Usage="Microsoft.Azure.Batch.JobPreparationTask.UserIdentity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.UserIdentity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Identität des Benutzers, unter der der Task ausgeführt wird.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn nicht angegeben, der Task als Nichtadministrator-eindeutige Benutzer an die Aufgabe ausgeführt.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="WaitForSuccess">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; WaitForSuccess { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; WaitForSuccess" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobPreparationTask.WaitForSuccess" />
      <MemberSignature Language="VB.NET" Value="Public Property WaitForSuccess As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.WaitForSuccess : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.JobPreparationTask.WaitForSuccess" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, ob der Batch-Dienst für den erfolgreichen Abschluss des Tasks "Auftrag zur Vorbereitung" vor dem Planen alle Aufgaben auf den Computeknoten warten soll.
            </summary>
        <value>To be added.</value>
        <remarks>
            Eine Auftrag zur Vorbereitung Taskausführung gilt als erfolgreich, wenn der ExitCode 0 ist. Wenn diese Eigenschaft nicht angegeben ist, wird der Standardwert lautet "true" vom Batch-Dienst zugewiesen.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>