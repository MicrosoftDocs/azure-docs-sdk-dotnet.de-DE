<Type Name="ServiceNameFormat" FullName="Microsoft.ServiceFabric.Services.ServiceNameFormat">
  <TypeSignature Language="C#" Value="public static class ServiceNameFormat" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ServiceNameFormat extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.ServiceNameFormat" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceNameFormat" />
  <TypeSignature Language="F#" Value="type ServiceNameFormat = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Diese Klasse stellt die Logik für die Namen der verschiedenen Elemente in der Manifestdatei aus dem Code ableiten. Es wird von Framework-Komponenten verwendet, wenn Namen in der API nicht angegeben sind und die Framework-Typen sie einen aussagekräftigen Namen, der den Diensttyp abgeleitet standardmäßig müssen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetEndpointName">
      <MemberSignature Language="C#" Value="public static string GetEndpointName (Type serviceInterfaceType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetEndpointName(class System.Type serviceInterfaceType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.ServiceNameFormat.GetEndpointName(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetEndpointName (serviceInterfaceType As Type) As String" />
      <MemberSignature Language="F#" Value="static member GetEndpointName : Type -&gt; string" Usage="Microsoft.ServiceFabric.Services.ServiceNameFormat.GetEndpointName serviceInterfaceType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceInterfaceType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="serviceInterfaceType">Diensttypname-Schnittstelle.</param>
        <summary>
            Ruft den Namen für die Ressource von Endpunkt für den angegebenen Diensttyp ab
            </summary>
        <returns>Der Name der endpunktressource.</returns>
        <remarks>
          <list type="bullet">
            <item>
                    Wenn der Typname ist <code>IMyService</code>, gibt diese Methode <code>MyServiceEndpoint</code> als Namen für die Endpoint-Ressource.
                </item>
            <item>
                    Wenn der Typname ist <code>Foo</code>, gibt diese Methode <code>FooServiceEndpoint</code> als Namen für die Endpoint-Ressource.
                </item>
          </list>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>