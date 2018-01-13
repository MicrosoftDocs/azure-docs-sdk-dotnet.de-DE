<Type Name="ExitOptions" FullName="Microsoft.Azure.Batch.Protocol.Models.ExitOptions">
  <TypeSignature Language="C#" Value="public class ExitOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExitOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.ExitOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class ExitOptions" />
  <TypeSignature Language="F#" Value="type ExitOptions = class" />
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
            Gibt an, wie der Batch-Dienst auf einem bestimmten beenden-Bedingung reagiert.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExitOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ExitOptions.#ctor" />
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
            Initialisiert eine neue Instanz der ExitOptions-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExitOptions (Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobAction&gt; jobAction = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.DependencyAction&gt; dependencyAction = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.JobAction&gt; jobAction, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.DependencyAction&gt; dependencyAction) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ExitOptions.#ctor(System.Nullable{Microsoft.Azure.Batch.Protocol.Models.JobAction},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.DependencyAction})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional jobAction As Nullable(Of JobAction) = null, Optional dependencyAction As Nullable(Of DependencyAction) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.ExitOptions : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobAction&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.DependencyAction&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.ExitOptions" Usage="new Microsoft.Azure.Batch.Protocol.Models.ExitOptions (jobAction, dependencyAction)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="jobAction" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobAction&gt;" />
        <Parameter Name="dependencyAction" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.DependencyAction&gt;" />
      </Parameters>
      <Docs>
        <param name="jobAction">Aktion für den Auftrag mit dem Task ausgeführt werden soll, wenn die Aufgabe abgeschlossen, mit der angegebenen beenden-Bedingung und den Auftrag OnTaskFailed-Eigenschaft ist ist "PerformExitOptionsJobAction".</param>
        <param name="dependencyAction">Eine Aktion, die der Batch-Dienst für Aufgaben ausführt, die von dieser Aufgabe abhängen.</param>
        <summary>
            Initialisiert eine neue Instanz der ExitOptions-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DependencyAction">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.DependencyAction&gt; DependencyAction { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.DependencyAction&gt; DependencyAction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ExitOptions.DependencyAction" />
      <MemberSignature Language="VB.NET" Value="Public Property DependencyAction As Nullable(Of DependencyAction)" />
      <MemberSignature Language="F#" Value="member this.DependencyAction : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.DependencyAction&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ExitOptions.DependencyAction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dependencyAction")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.DependencyAction&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen / definieren eine Aktion, die der Batch-Dienst für Aufgaben ausführt, die von dieser Aufgabe abhängen.
            </summary>
        <value>To be added.</value>
        <remarks>
            Der Standardwert ist "erfüllen" für den Exitcode 0 und "blockieren" für alle anderen beendigungsbedingungen. Wenn der Auftrag UsesTaskDependencies-Eigenschaft, auf "false" festgelegt ist, dann die Aktion Abhängigkeit-Eigenschaft gibt einen Fehler zurück und die Anforderung zum Hinzufügen eines Task tritt ein Fehler der ungültige Eigenschaft-Wert angegeben; Wenn Sie die REST-API direkt aufrufen, wird der HTTP-Statuscode 400 (Ungültige Anforderung). Folgende Werte sind möglich: "erfüllen", "blockieren"
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="JobAction">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobAction&gt; JobAction { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.JobAction&gt; JobAction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ExitOptions.JobAction" />
      <MemberSignature Language="VB.NET" Value="Public Property JobAction As Nullable(Of JobAction)" />
      <MemberSignature Language="F#" Value="member this.JobAction : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobAction&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ExitOptions.JobAction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="jobAction")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobAction&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Aktion für den Auftrag, den Task enthält, wenn die Aufgabe abgeschlossen, mit der angegebenen beenden-Bedingung ist, und der Auftrag OnTaskFailed-Eigenschaft ist "PerformExitOptionsJobAction" ausgeführt werden soll.
            </summary>
        <value>To be added.</value>
        <remarks>
            Die Standardeinstellung ist "none für Exitcode: 0" und für alle anderen beendigungsbedingungen beenden. Wenn der Auftrag OnTaskFailed-Eigenschaft "NoAction" ist, gebe ich diese Eigenschaft gibt einen Fehler zurück, und die Anforderung zum Hinzufügen eines Task tritt ein Fehler der ungültige Eigenschaft-Wert; Wenn Sie die REST-API direkt aufrufen, wird der HTTP-Statuscode 400 (Ungültige Anforderung). Folgende Werte sind möglich: 'none', 'disable', 'Beenden'
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>