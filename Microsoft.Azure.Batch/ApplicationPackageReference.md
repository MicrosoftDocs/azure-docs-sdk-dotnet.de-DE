<Type Name="ApplicationPackageReference" FullName="Microsoft.Azure.Batch.ApplicationPackageReference">
  <TypeSignature Language="C#" Value="public class ApplicationPackageReference" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationPackageReference extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.ApplicationPackageReference" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationPackageReference" />
  <TypeSignature Language="F#" Value="type ApplicationPackageReference = class&#xA;    interface ITransportObjectProvider&lt;ApplicationPackageReference&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            Ein Verweis auf ein Anwendungspaket erstellen, die bereitgestellt werden, um den Serverknoten.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationPackageReference ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ApplicationPackageReference.#ctor" />
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
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.ApplicationPackageReference" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationId">
      <MemberSignature Language="C#" Value="public string ApplicationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ApplicationPackageReference.ApplicationId" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationId As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationId : string with get, set" Usage="Microsoft.Azure.Batch.ApplicationPackageReference.ApplicationId" />
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
            Ruft ab oder legt die Id der Anwendung auf Serverknoten bereitgestellt werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public string Version { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ApplicationPackageReference.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As String" />
      <MemberSignature Language="F#" Value="member this.Version : string with get, set" Usage="Microsoft.Azure.Batch.ApplicationPackageReference.Version" />
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
            Ruft ab oder legt die Version der Anwendung auf Serverknoten bereitgestellt werden.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn nicht angegeben, wird die Standardversion der Anwendung, wie in den Anwendungseinstellungen definiert bereitgestellt. Wenn keine Standardversion in den Anwendungseinstellungen definiert ist, müssen Sie angeben, dass eine Version in der <see cref="T:Microsoft.Azure.Batch.ApplicationPackageReference" />.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>