<Type Name="ApplicationDefinitionKindFilter" FullName="System.Fabric.Description.ApplicationDefinitionKindFilter">
  <TypeSignature Language="C#" Value="public enum ApplicationDefinitionKindFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ApplicationDefinitionKindFilter extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ApplicationDefinitionKindFilter" />
  <TypeSignature Language="VB.NET" Value="Public Enum ApplicationDefinitionKindFilter" />
  <TypeSignature Language="F#" Value="type ApplicationDefinitionKindFilter = " />
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
      <para>Listet die Filter für den Abgleich der definitionsart von Anwendungen, die von der Abfrage zurückgegeben werden soll.</para>
    </summary>
    <remarks>Diese Enumeration verfügt über eine <see cref="T:System.FlagsAttribute" /> , mit dessen Hilfe einer bitweisen Kombination von Membern.</remarks>
  </Docs>
  <Members>
    <Member MemberName="All">
      <MemberSignature Language="C#" Value="All" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ApplicationDefinitionKindFilter All = int32(65535)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ApplicationDefinitionKindFilter.All" />
      <MemberSignature Language="VB.NET" Value="All" />
      <MemberSignature Language="F#" Value="All = 65535" Usage="System.Fabric.Description.ApplicationDefinitionKindFilter.All" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ApplicationDefinitionKindFilter</ReturnType>
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
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ApplicationDefinitionKindFilter Compose = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ApplicationDefinitionKindFilter.Compose" />
      <MemberSignature Language="VB.NET" Value="Compose" />
      <MemberSignature Language="F#" Value="Compose = 2" Usage="System.Fabric.Description.ApplicationDefinitionKindFilter.Compose" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ApplicationDefinitionKindFilter</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>Gibt einen Filter an, dass Übereinstimmungen Anwendungen durch definierten Datei(en) verfassen.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Default">
      <MemberSignature Language="C#" Value="Default" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ApplicationDefinitionKindFilter Default = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ApplicationDefinitionKindFilter.Default" />
      <MemberSignature Language="VB.NET" Value="Default" />
      <MemberSignature Language="F#" Value="Default = 0" Usage="System.Fabric.Description.ApplicationDefinitionKindFilter.Default" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ApplicationDefinitionKindFilter</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass kein Filter auf die definitionsart hinzugefügt wird.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="ServiceFabricApplicationDescription">
      <MemberSignature Language="C#" Value="ServiceFabricApplicationDescription" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ApplicationDefinitionKindFilter ServiceFabricApplicationDescription = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ApplicationDefinitionKindFilter.ServiceFabricApplicationDescription" />
      <MemberSignature Language="VB.NET" Value="ServiceFabricApplicationDescription" />
      <MemberSignature Language="F#" Value="ServiceFabricApplicationDescription = 1" Usage="System.Fabric.Description.ApplicationDefinitionKindFilter.ServiceFabricApplicationDescription" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ApplicationDefinitionKindFilter</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>Gibt einen Filter an, die Anwendungen, die durch definierten entspricht <see cref="T:System.Fabric.Description.ApplicationDescription" />.</para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>