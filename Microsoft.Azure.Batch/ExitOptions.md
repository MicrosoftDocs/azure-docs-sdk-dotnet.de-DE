<Type Name="ExitOptions" FullName="Microsoft.Azure.Batch.ExitOptions">
  <TypeSignature Language="C#" Value="public class ExitOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExitOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.ExitOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class ExitOptions" />
  <TypeSignature Language="F#" Value="type ExitOptions = class&#xA;    interface ITransportObjectProvider&lt;ExitOptions&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            Wie sollte der Batch-Dienst auf einem bestimmten beenden-Bedingung reagieren.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExitOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ExitOptions.#ctor" />
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
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.ExitOptions" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DependencyAction">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.DependencyAction&gt; DependencyAction { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.DependencyAction&gt; DependencyAction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ExitOptions.DependencyAction" />
      <MemberSignature Language="VB.NET" Value="Public Property DependencyAction As Nullable(Of DependencyAction)" />
      <MemberSignature Language="F#" Value="member this.DependencyAction : Nullable&lt;Microsoft.Azure.Batch.Common.DependencyAction&gt; with get, set" Usage="Microsoft.Azure.Batch.ExitOptions.DependencyAction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.DependencyAction&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert eine Aktion, die der Batch-Dienst für Aufgaben ausgeführt werden soll, die von dieser Aufgabe abhängen.
            </summary>
        <value>To be added.</value>
        <remarks>
            Die Standardeinstellung ist <see cref="F:Microsoft.Azure.Batch.Common.DependencyAction.Satisfy" /> für Exitcode: 0 (null) und <see cref="F:Microsoft.Azure.Batch.Common.DependencyAction.Block" /> für alle anderen beendigungsbedingungen. Wenn des Auftrags <see cref="P:Microsoft.Azure.Batch.CloudJob.UsesTaskDependencies" /> lautet "false", eine Aufgabe mit dieser Eigenschaft kann nicht hinzugefügt werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="JobAction">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.JobAction&gt; JobAction { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.JobAction&gt; JobAction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ExitOptions.JobAction" />
      <MemberSignature Language="VB.NET" Value="Public Property JobAction As Nullable(Of JobAction)" />
      <MemberSignature Language="F#" Value="member this.JobAction : Nullable&lt;Microsoft.Azure.Batch.Common.JobAction&gt; with get, set" Usage="Microsoft.Azure.Batch.ExitOptions.JobAction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.JobAction&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest Aktion für den Auftrag mit dem Task ausgeführt werden soll, wenn die Aufgabe abgeschlossen, mit der angegebenen beenden-Bedingung und des Auftrags ist <see cref="P:Microsoft.Azure.Batch.CloudJob.OnTaskFailure" /> Eigenschaft ist <see cref="F:Microsoft.Azure.Batch.Common.OnTaskFailure.PerformExitOptionsJobAction" />.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>