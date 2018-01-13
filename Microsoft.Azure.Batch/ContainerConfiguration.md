<Type Name="ContainerConfiguration" FullName="Microsoft.Azure.Batch.ContainerConfiguration">
  <TypeSignature Language="C#" Value="public class ContainerConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ContainerConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.ContainerConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class ContainerConfiguration" />
  <TypeSignature Language="F#" Value="type ContainerConfiguration = class&#xA;    interface ITransportObjectProvider&lt;ContainerConfiguration&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            Die Konfiguration für Anwendungspools Container aktiviert werden soll.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ContainerConfiguration.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.ContainerConfiguration" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerImageNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ContainerImageNames { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ContainerImageNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ContainerConfiguration.ContainerImageNames" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerImageNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ContainerImageNames : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Batch.ContainerConfiguration.ContainerImageNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Auflistung von containerimages.
            </summary>
        <value>To be added.</value>
        <remarks>
            Dies ist die vollständige bildverweises wie "Docker Pull" angegeben werden, würden. Ein Bild wird in der Standardeinstellung Docker-Registrierung bezogen werden, wenn das Image mit einer alternativen Registrierung vollständig qualifiziert ist.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerRegistries">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ContainerRegistry&gt; ContainerRegistries { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.ContainerRegistry&gt; ContainerRegistries" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ContainerConfiguration.ContainerRegistries" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerRegistries As IList(Of ContainerRegistry)" />
      <MemberSignature Language="F#" Value="member this.ContainerRegistries : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ContainerRegistry&gt; with get, set" Usage="Microsoft.Azure.Batch.ContainerConfiguration.ContainerRegistries" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ContainerRegistry&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert zusätzliche private Registrierungen, die von Containern abgerufen werden können.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn keine Bilder aus einer privaten Registrierung müssen die Anmeldeinformationen erforderlich ist heruntergeladen werden, müssen diese Anmeldeinformationen hier bereitgestellt werden.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>