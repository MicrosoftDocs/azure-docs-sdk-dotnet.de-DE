<Type Name="ApplicationDefinitionKind" FullName="System.Fabric.Query.ApplicationDefinitionKind">
  <TypeSignature Language="C#" Value="public enum ApplicationDefinitionKind" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ApplicationDefinitionKind extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ApplicationDefinitionKind" />
  <TypeSignature Language="VB.NET" Value="Public Enum ApplicationDefinitionKind" />
  <TypeSignature Language="F#" Value="type ApplicationDefinitionKind = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>Gibt die Art der Anwendung-Definition.</para>
      <para>Gibt den Mechanismus der Benutzer verwendet, um eine Service Fabric-Anwendung zu definieren. Service Fabric können Benutzer die Anwendung mit einem Service Fabric-anwendungsbeschreibung beschreiben oder Verfassen mithilfe von Dateien.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Compose">
      <MemberSignature Language="C#" Value="Compose" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ApplicationDefinitionKind Compose = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ApplicationDefinitionKind.Compose" />
      <MemberSignature Language="VB.NET" Value="Compose" />
      <MemberSignature Language="F#" Value="Compose = 1" Usage="System.Fabric.Query.ApplicationDefinitionKind.Compose" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ApplicationDefinitionKind</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass die Anwendung definiert ist von Dateien zu erstellen.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ApplicationDefinitionKind Invalid = int32(65535)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ApplicationDefinitionKind.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 65535" Usage="System.Fabric.Query.ApplicationDefinitionKind.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ApplicationDefinitionKind</ReturnType>
      </ReturnValue>
      <MemberValue>65535</MemberValue>
      <Docs>
        <summary>
          <para>Ungültig</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="ServiceFabricApplicationDescription">
      <MemberSignature Language="C#" Value="ServiceFabricApplicationDescription" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Query.ApplicationDefinitionKind ServiceFabricApplicationDescription = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Query.ApplicationDefinitionKind.ServiceFabricApplicationDescription" />
      <MemberSignature Language="VB.NET" Value="ServiceFabricApplicationDescription" />
      <MemberSignature Language="F#" Value="ServiceFabricApplicationDescription = 0" Usage="System.Fabric.Query.ApplicationDefinitionKind.ServiceFabricApplicationDescription" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ApplicationDefinitionKind</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass von die Anwendung definiert wird <see cref="T:System.Fabric.Description.ApplicationDescription" />.</para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>