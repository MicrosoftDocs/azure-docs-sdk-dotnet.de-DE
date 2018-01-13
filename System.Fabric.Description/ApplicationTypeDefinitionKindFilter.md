<Type Name="ApplicationTypeDefinitionKindFilter" FullName="System.Fabric.Description.ApplicationTypeDefinitionKindFilter">
  <TypeSignature Language="C#" Value="public enum ApplicationTypeDefinitionKindFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ApplicationTypeDefinitionKindFilter extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ApplicationTypeDefinitionKindFilter" />
  <TypeSignature Language="VB.NET" Value="Public Enum ApplicationTypeDefinitionKindFilter" />
  <TypeSignature Language="F#" Value="type ApplicationTypeDefinitionKindFilter = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Attributes>
    <Attribute>
      <AttributeName>System.Flags</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para>Listet die Filter für den Abgleich der definitionsart Anwendungen-Typ, der von der Abfrage zurückgegeben werden soll.</para>
    </summary>
    <remarks>Diese Enumeration verfügt über eine <see cref="T:System.FlagsAttribute" /> , mit dessen Hilfe einer bitweisen Kombination von Membern.</remarks>
  </Docs>
  <Members>
    <Member MemberName="All">
      <MemberSignature Language="C#" Value="All" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ApplicationTypeDefinitionKindFilter All = int32(65535)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ApplicationTypeDefinitionKindFilter.All" />
      <MemberSignature Language="VB.NET" Value="All" />
      <MemberSignature Language="F#" Value="All = 65535" Usage="System.Fabric.Description.ApplicationTypeDefinitionKindFilter.All" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ApplicationTypeDefinitionKindFilter</ReturnType>
      </ReturnValue>
      <MemberValue>65535</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass kein Filter auf die definitionsart hinzugefügt wird.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Compose">
      <MemberSignature Language="C#" Value="Compose" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ApplicationTypeDefinitionKindFilter Compose = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ApplicationTypeDefinitionKindFilter.Compose" />
      <MemberSignature Language="VB.NET" Value="Compose" />
      <MemberSignature Language="F#" Value="Compose = 2" Usage="System.Fabric.Description.ApplicationTypeDefinitionKindFilter.Compose" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ApplicationTypeDefinitionKindFilter</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>Gibt einen Filter, der Anwendungstypen definiert und erstellt implizit als Teil einer Bereitstellung verfassen entspricht.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Default">
      <MemberSignature Language="C#" Value="Default" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ApplicationTypeDefinitionKindFilter Default = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ApplicationTypeDefinitionKindFilter.Default" />
      <MemberSignature Language="VB.NET" Value="Default" />
      <MemberSignature Language="F#" Value="Default = 0" Usage="System.Fabric.Description.ApplicationTypeDefinitionKindFilter.Default" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ApplicationTypeDefinitionKindFilter</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass kein Filter auf die definitionsart hinzugefügt wird.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="ServiceFabricApplicationPackage">
      <MemberSignature Language="C#" Value="ServiceFabricApplicationPackage" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ApplicationTypeDefinitionKindFilter ServiceFabricApplicationPackage = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ApplicationTypeDefinitionKindFilter.ServiceFabricApplicationPackage" />
      <MemberSignature Language="VB.NET" Value="ServiceFabricApplicationPackage" />
      <MemberSignature Language="F#" Value="ServiceFabricApplicationPackage = 1" Usage="System.Fabric.Description.ApplicationTypeDefinitionKindFilter.ServiceFabricApplicationPackage" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ApplicationTypeDefinitionKindFilter</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>Gibt einen Filter, der Anwendungstypen definiert und erstellt, indem ein vom Benutzer bereitgestellte Service Fabric-Anwendungspaket entspricht.</para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>