<Type Name="EnvironmentSetting" FullName="Microsoft.Azure.Batch.EnvironmentSetting">
  <TypeSignature Language="C#" Value="public class EnvironmentSetting" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EnvironmentSetting extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.EnvironmentSetting" />
  <TypeSignature Language="VB.NET" Value="Public Class EnvironmentSetting" />
  <TypeSignature Language="F#" Value="type EnvironmentSetting = class&#xA;    interface ITransportObjectProvider&lt;EnvironmentSetting&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="56eb8-101">Eine Umgebungsvariable für eine Aufgabenprozess, z. B. eine Auftragstasks, Startaufgabe, Auftrags-Manager-Aufgabe oder Auftragstasks zur Vorbereitung oder der Veröffentlichung festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="56eb8-101">An environment variable to be set on a task process, such as a job task, start task, job manager task, or job preparation or release task.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EnvironmentSetting (string name, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.EnvironmentSetting.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, value As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.EnvironmentSetting : string * string -&gt; Microsoft.Azure.Batch.EnvironmentSetting" Usage="new Microsoft.Azure.Batch.EnvironmentSetting (name, value)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="56eb8-102">Der Name der Umgebungsvariablen.</span><span class="sxs-lookup"><span data-stu-id="56eb8-102">The name of the environment variable.</span></span></param>
        <param name="value"><span data-ttu-id="56eb8-103">Der Wert der Umgebungsvariablen.</span><span class="sxs-lookup"><span data-stu-id="56eb8-103">The value of the environment variable.</span></span></param>
        <summary>
            <span data-ttu-id="56eb8-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.EnvironmentSetting" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="56eb8-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.EnvironmentSetting" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.EnvironmentSetting.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Batch.EnvironmentSetting.Name" />
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
            <span data-ttu-id="56eb8-105">Ruft den Namen der Umgebungsvariablen ab.</span><span class="sxs-lookup"><span data-stu-id="56eb8-105">Gets the name of the environment variable.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public string Value { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.EnvironmentSetting.Value" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Value As String" />
      <MemberSignature Language="F#" Value="member this.Value : string" Usage="Microsoft.Azure.Batch.EnvironmentSetting.Value" />
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
            <span data-ttu-id="56eb8-106">Ruft den Wert der Umgebungsvariablen ab.</span><span class="sxs-lookup"><span data-stu-id="56eb8-106">Gets the value of the environment variable.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>