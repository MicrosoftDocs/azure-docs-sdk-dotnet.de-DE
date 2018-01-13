<Type Name="ServiceTypeInformation" FullName="Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceTypeInformation">
  <TypeSignature Language="C#" Value="public sealed class ServiceTypeInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceTypeInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceTypeInformation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceTypeInformation" />
  <TypeSignature Language="F#" Value="type ServiceTypeInformation = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Gibt die Klasse, die von der ServiceRemoting verwendet, um die vom Dienst implementierten Schnittstellen zu suchen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceTypeInformation Get (Type serviceType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceTypeInformation Get(class System.Type serviceType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceTypeInformation.Get(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Get (serviceType As Type) As ServiceTypeInformation" />
      <MemberSignature Language="F#" Value="static member Get : Type -&gt; Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceTypeInformation" Usage="Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceTypeInformation.Get serviceType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceTypeInformation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="serviceType">Typ, um zu überprüfen</param>
        <summary>
            Factorymethode, die ein ServiceTypeInformation-Objekt aus dem angegebenen Typ erstellt.
            </summary>
        <returns>ServiceTypeInformation</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImplementationType">
      <MemberSignature Language="C#" Value="public Type ImplementationType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Type ImplementationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceTypeInformation.ImplementationType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ImplementationType As Type" />
      <MemberSignature Language="F#" Value="member this.ImplementationType : Type" Usage="Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceTypeInformation.ImplementationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Typ der Klasse, die die Dienstschnittstelle implementiert.
            </summary>
        <value>
          <see cref="T:System.Type" />implementieren die Dienstschnittstelle der-Klasse.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InterfaceTypes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Type&gt; InterfaceTypes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class System.Type&gt; InterfaceTypes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceTypeInformation.InterfaceTypes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InterfaceTypes As IEnumerable(Of Type)" />
      <MemberSignature Language="F#" Value="member this.InterfaceTypes : seq&lt;Type&gt;" Usage="Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceTypeInformation.InterfaceTypes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.Type&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, ob die Schnittstelle implementiert.
            </summary>
        <value>Liste der Schnittstellentypen</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsAbstract">
      <MemberSignature Language="C#" Value="public bool IsAbstract { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsAbstract" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceTypeInformation.IsAbstract" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsAbstract As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsAbstract : bool" Usage="Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceTypeInformation.IsAbstract" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, wenn die Schnittstelle implementierende Klasse abstrakt ist.
            </summary>
        <value>"true", wenn die Schnittstelle implementierende Klasse ist abstrakt, andernfalls "false".</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGet">
      <MemberSignature Language="C#" Value="public static bool TryGet (Type serviceType, out Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceTypeInformation serviceTypeInformation);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool TryGet(class System.Type serviceType, [out] class Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceTypeInformation&amp; serviceTypeInformation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceTypeInformation.TryGet(System.Type,Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceTypeInformation@)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function TryGet (serviceType As Type, ByRef serviceTypeInformation As ServiceTypeInformation) As Boolean" />
      <MemberSignature Language="F#" Value="static member TryGet : Type *  -&gt; bool" Usage="Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceTypeInformation.TryGet (serviceType, serviceTypeInformation)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceType" Type="System.Type" />
        <Parameter Name="serviceTypeInformation" Type="Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceTypeInformation&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="serviceType">Typ, um zu überprüfen</param>
        <param name="serviceTypeInformation">Der konstruierte ServiceTypeInformation</param>
        <summary>
            Ruft die Factory-Methode, die ein ServiceTypeInformation-Objekt aus dem angegebenen Typ erstellt.
            </summary>
        <returns>"true", wenn die angegebenen Diensttyp einen Dienst, "false", andernfalls ist</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>