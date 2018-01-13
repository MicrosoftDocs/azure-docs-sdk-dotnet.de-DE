<Type Name="TaskUpdateParameter" FullName="Microsoft.Azure.Batch.Protocol.Models.TaskUpdateParameter">
  <TypeSignature Language="C#" Value="public class TaskUpdateParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskUpdateParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.TaskUpdateParameter" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskUpdateParameter" />
  <TypeSignature Language="F#" Value="type TaskUpdateParameter = class" />
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
            Der Satz von Änderungen an einer Aufgabe vorgenommen werden müssen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskUpdateParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskUpdateParameter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der TaskUpdateParameter-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskUpdateParameter (Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskUpdateParameter.#ctor(Microsoft.Azure.Batch.Protocol.Models.TaskConstraints)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional constraints As TaskConstraints = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.TaskUpdateParameter : Microsoft.Azure.Batch.Protocol.Models.TaskConstraints -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskUpdateParameter" Usage="new Microsoft.Azure.Batch.Protocol.Models.TaskUpdateParameter constraints" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="constraints" Type="Microsoft.Azure.Batch.Protocol.Models.TaskConstraints" />
      </Parameters>
      <Docs>
        <param name="constraints">Einschränkungen, die für diese Aufgabe gelten.</param>
        <summary>
            Initialisiert eine neue Instanz der TaskUpdateParameter-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Constraints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskConstraints Constraints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskConstraints Constraints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskUpdateParameter.Constraints" />
      <MemberSignature Language="VB.NET" Value="Public Property Constraints As TaskConstraints" />
      <MemberSignature Language="F#" Value="member this.Constraints : Microsoft.Azure.Batch.Protocol.Models.TaskConstraints with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskUpdateParameter.Constraints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="constraints")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskConstraints</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest, die für diese Aufgabe gelten Einschränkungen.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn nicht angegeben, wird die Aufgabe das Default-Einschränkungen angegeben. Für Vorgänge mit mehreren Instanzen aktualisieren die Aufbewahrungsdauer gilt nur für die primäre Aufgabe und Teilvorgänge nicht.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>