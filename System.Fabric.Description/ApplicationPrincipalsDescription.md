<Type Name="ApplicationPrincipalsDescription" FullName="System.Fabric.Description.ApplicationPrincipalsDescription">
  <TypeSignature Language="C#" Value="public sealed class ApplicationPrincipalsDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationPrincipalsDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ApplicationPrincipalsDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationPrincipalsDescription" />
  <TypeSignature Language="F#" Value="type ApplicationPrincipalsDescription = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Beschreibt die Anwendungsprinzipale des Diensts an.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationPrincipalsDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ApplicationPrincipalsDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Erstellt und initialisiert ein <see cref="T:System.Fabric.Description.ApplicationPrincipalsDescription" /> Objekt. </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Groups">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Description.SecurityGroupDescription&gt; Groups { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Description.SecurityGroupDescription&gt; Groups" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationPrincipalsDescription.Groups" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Groups As IList(Of SecurityGroupDescription)" />
      <MemberSignature Language="F#" Value="member this.Groups : System.Collections.Generic.IList&lt;System.Fabric.Description.SecurityGroupDescription&gt;" Usage="System.Fabric.Description.ApplicationPrincipalsDescription.Groups" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Description.SecurityGroupDescription&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Gruppen, die als Teil der Anwendung Einrichten der Umgebung im Manifest Anwendung erstellt werden müssen.</para>
        </summary>
        <value>
          <para>Die Gruppen, die als Teil der Anwendung Einrichten der Umgebung im Manifest Anwendung erstellt werden müssen.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Users">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Description.SecurityUserDescription&gt; Users { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Description.SecurityUserDescription&gt; Users" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationPrincipalsDescription.Users" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Users As IList(Of SecurityUserDescription)" />
      <MemberSignature Language="F#" Value="member this.Users : System.Collections.Generic.IList&lt;System.Fabric.Description.SecurityUserDescription&gt;" Usage="System.Fabric.Description.ApplicationPrincipalsDescription.Users" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Description.SecurityUserDescription&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Benutzer, die als Teil der Anwendung Einrichten der Umgebung im Manifest Anwendung erstellt werden müssen.</para>
        </summary>
        <value>
          <para>Die Benutzer, die als Teil der Anwendung Einrichten der Umgebung im Manifest Anwendung erstellt werden müssen.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>